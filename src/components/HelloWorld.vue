<template>
  <div>
    <button @click="btnFun"> Toast </button>

  </div>
</template>

<script>
import { Toast } from 'vant';
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  methods:{
    btnFun(){
      Toast({
        message: '自定义图标',
        icon: 'like-o',
      })
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

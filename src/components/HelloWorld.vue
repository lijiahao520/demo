<template>
  <div class="hello">
    <ul>
      <li>
        <i class="icon-gouwuche iconfont"></i>
        收银
        </li>
      <li><i class="icon-gouwuche iconfont"></i>商品</li>
      <li><i class="icon-gouwuche iconfont"></i>店铺</li>
      <li><i class="icon-gouwuche iconfont"></i>VIP</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
.iconfont{
  display: block;
  font-size: 200%;
}
li {
  text-align: center;
  display: block;
  width: 100%;
  height: 100px;
  /* line-height: 100px; */
}
a {
  color: #42b983;
}
</style>

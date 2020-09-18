<template>
  <div>
    <div class="container clearfix">header</div>
    <div class="pv">
      <i class="ll">xxx人已浏览</i>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.container {
  position: relative;
  width: 100%;
  height: 0;
  padding-top: 33.5%;
  color: #fff;
  font-size: 0.28rem;
  text-align: center;
  background: url(https://img1.dxycdn.com/2020/0314/863/3401956761707181858-2.png)
    no-repeat;
  background-size: cover;
  position: relative;
}
.pv {
  position: absolute;
  right: 0;
  top: 10px;
  color: #fff;
  font-size: 12px;
  height: 24px;
  line-height: 24px;
  border-top-left-radius: 24px;
  border-bottom-left-radius: 24px;
  background-color: rgba(19, 15, 133, 0.6);
}
.pv .ll {
  padding: 0 10px;
}
</style>

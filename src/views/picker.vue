<template>
  <div class="wrapper">
    <div class="item "><div class="a"></div></div>
    <div class="item "><div class="b">水电费</div></div>
    <div class="item "><div class="c">水电费</div></div>
  </div>
</template>

<script>
export default {
  name: "picker"
};
</script>

<style scoped lang="stylus">
.wrapper {
  display flex
  width: 100%
}

.item {
  flex: 1;
  /*display table-cell*/
  /*vertical-align bottom*/
}

.a {
  height: 100px;
  background: rosybrown;
}

.b {
  height 50px;
  background aqua
}

.c {
  height: 150px;
  background green
}
</style>
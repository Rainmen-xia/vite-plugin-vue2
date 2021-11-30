<template>
  <div>
    <h2>CSS Modules</h2>
    <div class="css-modules-sfc" >
      &lt;style module&gt; - this should be blue
    <div class="icon">svg</div>
    </div>

  </div>
</template>

<script>

export default {
  data: () => ({  })
}
</script>

<style scoped lang="less">
.icon{
  display: inline-block;
  width: 18px;
  height: 18px;
  background: url("./icon-right.svg") no-repeat
    center center;
  vertical-align: middle;
  margin-left: 8px;
}
</style>

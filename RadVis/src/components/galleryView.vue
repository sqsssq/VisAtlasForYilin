<!--
 * @Author: Qing Shi
 * @LastEditTime: 2022-04-07 18:52:06
 * @Knowledge: 
 * @Description: 
 * @Attention: 
-->
<template>
  <div id="titleBar">
    <span style="position: absolute; left: 40%;">{{ viewName }}</span>
    <span style="float: right">
      <form
        id="select-distance"
        style="margin-top:0;margin-right:18px"
      >

        <input
          type="radio"
          id="metricChoice1"
          name="contact"
          value="cosine"
          checked="checked"
        >
        <label for="metricChoice1">Cosine</label>

        <input
          type="radio"
          id="metricChoice2"
          name="contact"
          value="radviz"
          style="margin-left:13px"
        >
        <label for="metricChoice2">Projection</label>

      </form>
    </span>

  </div>
</template>

<script>
export default {
  data () {
    return {
      viewName: "Visualization Gallery"
    }
  }
}
</script>

<style>
</style>
<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name:'Tabbar'
};
</script>

<style>
#tab-bar {
  display: flex;
  position: fixed;
  background-color: #f6f6f6;
  bottom: 0px;
  left: 0;
  right: 0;
  box-shadow: 0px -1px 1px rgba(100, 100,100, 0.15);
}

</style>

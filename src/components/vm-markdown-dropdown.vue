<template>
    <div class="vm-markdown-dropdown">
      <slot></slot>
      <span class="block"></span>
    </div>
</template>
<style lang="scss">
  .vm-markdown-dropdown{
    position: absolute;
    background: #fff;
    left: 0;
    top: 35px;
    border-radius: 4px;
    border: 1px solid #eeeff1;
    box-shadow: 0 0 4px rgba(0,0,0,.05);
    z-index: 999;
    .block{
      width: 100%;
      height: 15px;
      background: red;
      position: absolute;
      left: 0;
      top: -15px;
      opacity: 0;
    }
  }
</style>
<script>
export default {
  name: 'VmMarkdownDropDown'
}
</script>

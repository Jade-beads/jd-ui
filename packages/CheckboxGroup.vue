
<template>
  <div class="jd-checkbox-group">
    <slot></slot>
  </div>
</template>
<script>
export default {
  name: 'jd-checkbox-group',
  provide () {
    return {
      CheckboxGroup: this
    }
  },
  props: {
    value: {
      type: Array
    }
  }
}
</script>
<template>
  <div>
    <button class="btn btn-success" @click="tang">tang</button>
    <button class="btn btn-success" @click="giam">giam</button>
  </div>
</template>
 
<script>
export default {
  data() {
    return {};
  },
  methods: {
    tang() {
      this.$emit('updated', 1)
    },
    giam() {
      this.$emit('updated', -1)
    }
  }
};
</script>

<style >
</style>
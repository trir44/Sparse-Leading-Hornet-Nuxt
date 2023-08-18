<template>
  <main class="component-container" v-bind:class="rootClassName"></main>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {
    rootClassName: String,
  },
}
</script>

<style scoped>
.component-container {
  width: 997px;
  height: 400px;
  display: flex;
  z-index: 100;
  position: relative;
  box-shadow: 5px 5px 10px 0px #d4d4d4;
  transition: 0.3s;
  align-items: flex-start;
  border-color: var(--dl-color-gray-black);
  border-style: solid;
  border-width: 0px;
  border-radius: var(--dl-radius-radius-radius8);
  flex-direction: column;
  background-color: var(--dl-color-primary-bl1);
}

</style>

<template>
<p>{{ msg }}</p>
</template>
<script>
  /**
   * Returns an object containing the data for the Vue component.
   *
   * @return {Object} An object with a single property `msg`, which is a string
   * representing the message to be displayed.
   */
export default {
  name: 'App',

     /**
   * Returns an object containing the data for the Vue component.
   *
   * @return {Object} An object with a single property `msg`, which is a string
   * representing the message to be displayed.
   */
  data() {
    return {
      msg: 'Test Application'
    }
  }}
</script>

<template>
  <select v-model="comoponentName">
    <option value="Home">Home</option>
    <option value="About">About</option>
  </select>
  <keep-alive>
    <component :is="comoponentName"></component>
  </keep-alive>
</template>
<script>
import Home from './components/Home.vue'
import About from './components/About.vue'
/**
 * Returns an object containing the data for the Vue component.
 *
 * @return {Object} An object with a single property `msg`, which is a string
 * representing the message to be displayed.
 */
export default {
  name: 'App',
  components: {
    About,
    Home
  },

  /**
* Returns an object containing the data for the Vue component.
*
* @return {Object} An object with a single property `msg`, which is a string
* representing the message to be displayed.
*/
  data() {
    return {
      comoponentName: "Home",
    }
  }
}
</script>

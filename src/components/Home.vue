<template>
    <!-- The template section of the Home component -->
    <h1>Home Page</h1>
</template>

<script>
/**
 * @file Home.vue
 * @description The Home component represents the main page of the application.
 * It contains the template and logic for the home page.
 */

export default {
    // Component options
    // name: 'Home',
    unmounted() {
        console.log('Home component unmounted');
    },
    activated() {
        console.log('Home component activated');
    },
    deactivated() {
        console.log('Home component deactivated');
    },
}
</script>

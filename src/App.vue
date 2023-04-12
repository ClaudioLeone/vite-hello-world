<script>
import AppTitle from "./components/AppTitle.vue";  //1] Import our component

export default {
  components: {                                    //2] Instantiate our component as an object (named 'components') property
    AppTitle                                       //<< The component
  },
  data() {
    return {

    }
  }
}
</script>

<template>
  <h2>...Hello Vue, Vite, Node JS and obviously WORLD...</h2>
  <AppTitle/>
</template>

<style></style>
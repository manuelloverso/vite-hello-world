<script>
import MyComponent from "./components/My_component.vue";

export default {
  data() {
    return {
      hello: "Hello Vite",
    };
  },

  components: {
    MyComponent,
  },
};
</script>

<template>
  <h1>{{ hello }}</h1>
  <MyComponent />
</template>

<style></style>

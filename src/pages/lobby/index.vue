<template>
  <div>
    <img width="25%" src="/assets/Bear-And-Cub-Logo.svg">
    <HelloWorld :msg="$attrs.message"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "page-about",
  title: "LT2D",
  components: { HelloWorld },
  makeSureJSONWorks: ""
};
</script>
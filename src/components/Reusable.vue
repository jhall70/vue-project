<template>
  <h1>This is the {{ title }} part of the page.</h1>
</template>

<script>
export default {
  props: {
    title: String,
  },
};
</script>

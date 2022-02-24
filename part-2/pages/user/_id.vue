<template>
  <h1>
    profile dinamis
    {{ $route.params.id }}
  </h1>
</template>

<script>
export default {
  validate({ params }) {
    return /^\d+$/.test(params.id);
  },
};
</script>

<style></style>

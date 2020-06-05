<template>
  <div class="fine">
    fine
    <div class="fine__not">
      not fine
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style lang="postcss" scoped>
.fine {
  color: green;

  &__not {
    color: red;
  }
}
</style>

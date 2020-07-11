<template>
  <div class="homepage" role="homepage">
    <div>
      Kahoot!
    </div>
    <input
      class="homepage__input"
      placeholder="You Nick Name"
      aria-label="nickName"
    />
    <button>Enter</button>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.homepage {
  display: grid;
  grid-template-rows: 2fr 1fr 1fr;
  width: 20vw;
  margin: 0 auto;
  &__input {
    text-align: center;
  }
}
</style>

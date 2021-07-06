<template>
  <div class="navbar">
    <div class="navbar__container">
      <div class="navbar__logo">
        <img src="@/assets/logo.svg" alt="Piggy bank" />
      </div>
      <ul class="navbar__links">
        <li class="navbar__link">Assets</li>
        <li class="navbar__link">Account</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navbar {
  color: $white;

  &__container {
    margin: 0px 32px;
  }

  &__links {
    font-weight: 12px;
  }
}
</style>

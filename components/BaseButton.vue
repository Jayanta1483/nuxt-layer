<template>
  <div>
    <p>Layer Base Button</p>
  <button class="btn">
    <slot />
  </button>
  </div>
</template>

<style scoped>
.btn {
  padding: 8px 16px;
  background: black;
  color: white;
  border-radius: 6px;
}
</style>
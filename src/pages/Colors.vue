<template>
  <q-page class="g-pa-xl">
    <section class="q-mb-xl">
      <div class="text-h4">Brand Colors</div>
      <q-separator class="q-my-md" />
      <div class="text-white bg-primary">primary</div>
      <div class="text-white bg-secondary">secondary</div>
      <div class="text-white bg-accent">accent</div>
      <div class="text-white bg-dark">dark</div>
      <div class="text-white bg-positive">positive</div>
      <div class="text-white bg-negative">negative</div>
      <div class="text-white bg-info">info</div>
      <div class="text-white bg-warning">warning</div>
      <div class="text-white bg-orange-4">bg-orange-4</div>
      <div class="text-white bg-light-green-5">light-green-5</div>
      <div class="bg-color">blue-grey-1</div>
      <p>Variables</p>
    </section>
    <section class="q-mb-xl">
      <div class="text-h4">Components</div>
      <q-separator class="q-my-md" />
      <div class="q-pa-md q-gutter-sm">
        <q-btn color="primary" label="primary" />
        <q-btn color="white" text-color="black" label="standard" />
        <q-btn color="secondary" label="secondary" />
        <q-btn color="amber" glossy label="amber" />
        <q-btn color="brown-5" glossy label="brown-5" />
        <q-btn color="deep-orange" glossy label="Deep orange" />
        <q-btn color="purple" label="purple" />
        <q-btn color="black" label="black" />
        <q-btn color="error" label="error" />
      </div>
    </section>
  </q-page>
</template>

<script setup></script>
<style lang="scss" scoped>
p {
  color: $red;
  background-color: $grey-5;
}
.txt-error {
  color: $red;
}
.bg-color {
  background: $red;
}
</style>

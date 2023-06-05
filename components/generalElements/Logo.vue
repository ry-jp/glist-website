<script setup>
const runtimeConfig = useRuntimeConfig();
const logoUrl = runtimeConfig?.public?.LOGO || null;
</script>

<template>
<div class="flex flex-col">
  <NuxtLink to="/">
    <img src="~/public/logo.svg" alt="GLISTUSA" class=" h-16 justify-center" />
    <div>
      <span class="text-white font-bold">GLISTUSA</span>
    </div>
  </NuxtLink>
</div>
</template>

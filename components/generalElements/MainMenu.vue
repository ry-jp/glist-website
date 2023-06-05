<template>
  <nav>
    <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/products">Clothes</NuxtLink>
    <NuxtLink to="/categories">{{ $t('messages.shop.category', 2) }}</NuxtLink>
    <NuxtLink to="/contact">{{ $t('messages.general.contact') }}</NuxtLink>
  </nav>
</template>

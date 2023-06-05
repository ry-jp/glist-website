<template>
  <header class="bg-black top-0 shadow-light-500 z-40 sticky">
    <div class="container flex py-4 items-center justify-between">
      <div class="flex items-center">
        <MenuTrigger class="md:hidden" />
        <Logo class="md:w-[160px]" />
      </div>
      <MainMenu class="text-sm text-white gap-6 items-center hidden md:flex lg:px-4" />
      <div class="flex gap-4 justify-end items-center md:w-[160px]">
        <SignInLink class="text-white" />
        <CartTrigger class="text-white" />
      </div>
    </div>
  </header>
</template>

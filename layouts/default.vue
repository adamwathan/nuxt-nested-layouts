<template>
  <div class="antialiased text-gray-900 h-screen flex flex-col">
    <div class="relative px-8 py-4 shadow flex items-center flex-shrink-0">
      <nuxt-link to="/">
        <svg class="w-10 h-10" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M2 10L20 0l18 10v20L20 40 2 30V10z" fill="#C3DAFE"/><path d="M38 30V10L20 20v20l18-10z" fill="#434190"/><path d="M2 10v20l18 10V20L2 10z" fill="#667EEA"/></svg>
      </nuxt-link>
      <nuxt-link to="/docs/page-1" class="ml-16 text-lg font-semibold">Docs</nuxt-link>
      <nuxt-link to="/examples/page-1" class="ml-12 text-lg font-semibold">Examples</nuxt-link>
    </div>
    <nuxt />
  </div>
</template>

<style src="../assets/tailwind.css"></style>

<template>
    <div class="container mx-auto">
        <header class="flex justify-between items-center mt-5">
            <div>
                <NuxtLink to="/" class="text-xl font-semibold p-2 hover:bg-gray-200">Jishad P</NuxtLink>
            </div>
            <Menu></Menu>
        </header>
        <main class="p-2">
            <slot />
        </main>
        
        
    </div>

</template>

<script setup>
useHead({
  titleTemplate: '%s - KarCare',
  link: [
    {
      rel: 'preconnect',
      href: 'https://fonts.googleapis.com'
    },
    {
      rel: 'stylesheet',
      href: 'https://fonts.googleapis.com/css2?family=Roboto&display=swap',
      crossorigin: ''
    }
  ]
})
</script>
<style>
body{
    font-family: Roboto;
}
</style>
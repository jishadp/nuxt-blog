<template>
    <div>
      <h1>Blog Item Page</h1>
    </div>
    <div>
      <h4>Post Slug is {{ route.params.slug }}</h4>

      
    </div>
</template>

<script setup>
const route = useRoute()
console.log(route);
</script>
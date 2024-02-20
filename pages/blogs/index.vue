<template>
    <div>
     <h1>Blog Posts Page</h1>
     <nav>
      <ul>
        <li> <NuxtLink :to="{name:'blogs-slug','params':{'slug':'xxx'}}">Blog XXX</NuxtLink> </li>
        <li> <NuxtLink :to="{name:'blogs-slug','params':{'slug':'yyy'}}">Blog yyy</NuxtLink> </li>
      </ul>
    </nav>
    </div>
  </template>
  <script setup>
  useSeoMeta({
    title: 'Blogs',
  })
  </script>
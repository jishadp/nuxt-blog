<template>
    <div>
        <h3>Providers</h3>
        <ul>
            <li v-for="provider in providers">
                <div>Name : {{ provider.name }}</div>
                <div>Year : {{ provider.year }}</div>
            </li>
        </ul>
    </div>
</template>
<script setup>
useSeoMeta({
    title:'Providers'
})
const { data: responseData } = await useFetch('https://reqres.in/api/user?page=2') // $fetch,useFetch,useAsyncData
const providers = ref(responseData.value.data);

</script>
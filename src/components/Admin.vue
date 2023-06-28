<template>
    <h1>
        ADMIN
    </h1>
    <div v-for="property in properties" :key="property.id">
        <router-link>

        </router-link>

    </div>
</template>

<script>
    export default {
        data(){
            let data = fetch('will be fecthing here')
        },
        // Provide more logic and Methods
        
    }
</script>

<style>

</style>
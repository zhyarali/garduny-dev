<template>
    
        <v-col  align="center" md="3" class="my-5">
            <nuxt-link :to="'/projects/'+link">
            <v-img  style="cursor:pointer" max-width="280" class="rounded-lg" 
            :src="'/img/'+image" height="220"></v-img>
            </nuxt-link>
        </v-col>
    
</template>

<script>
    export default {
        props:['image','link']
    }
</script>

<style lang="scss" scoped>

</style>
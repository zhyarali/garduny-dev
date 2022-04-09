<template>
 
            <v-col
            cols="2">

            <v-card  v-tooltip="tooltipText" style="cursor:pointer"  height="70" max-width="140"  class=" rounded-lg d-flex justify-center align-center" >
               <v-img
                tile
                max-width="40"
                :src="'/'+image+'.svg'"></v-img>
                
            </v-card>
 
          </v-col>
   
</template>

<script>
    export default {
        props:['image','tooltipText']
    }
</script>

<style lang="scss" scoped>

</style>
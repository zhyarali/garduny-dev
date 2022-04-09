<template>
     
          <v-col data-aos="slide-up" data-aos-duration="2000"   cols="10" md="4" >   
            <v-card
            class="mx-auto rounded-lg"
            width="304px"
            align="center"
            style="cursor:pointer"
            :to="'projects/'+link"
        >
            <v-img
            :src="'img/'+image"
            height="280px"
            ></v-img>

            <v-card-title  class="justify-center text-justify ">
                <div  class=" text-truncate">
                    {{title}}
                </div>
            </v-card-title>

            <p class="justify-center" style="    font-size: 0.875rem;
    font-weight: 400;
    line-height:1.975rem;
    letter-spacing: 0.0071428571em;">
                {{type}}
            </p>
        </v-card>

          </v-col>

 
</template>

<script>
    export default {
        props:['image','title','type','link']
    }
</script>

<style lang="scss" scoped>

</style>
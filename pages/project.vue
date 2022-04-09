<template>
    <div>
         <v-container class="">
            <!-- projects -->
<v-row class="justify-center mt-16" data-aos="zoom-in" data-aos-duration="2000">
   <h1>See My Works Which
Will Amaze You!</h1>
 </v-row>

<v-row class="justify-center mb-10 mt-10 flex-wrap">
          <projectCard link="health" image="1.jpg" title="Health Management System" type="Mobile App"/>
          <projectCard link="Choveen" image="4.jpg" title="Choveen" type="Web Application"/>
          <projectCard link="health" image="2.jpg" title="Health Management System" type="Mobile App"/>
          <projectCard link="health" image="3.jpg" title="Health Management System" type="Mobile App"/>
          <projectCard link="health" image="2.jpg" title="Health Management System" type="Mobile App"/>
          <projectCard link="health" image="1.jpg" title="Health Management System" type="Mobile App"/>
</v-row> 
          </v-container>
    </div>
</template>

<script>
import projectCard from "../components/project-card.vue";
    export default {
        components:{
            projectCard
        }
    }
</script>

<style lang="scss" scoped>

</style>
<template>
    <div>
         <v-container class="">

         <v-row class="mt-10 mdAndsmCenter">
           <h1 >Healh Management System</h1>
         </v-row>

          <v-row class="mt-8 d-flex flex-wrap mdAndsmCenter">

            <div class="d-flex mr-6">
                <span class="material-icons-round mr-3">schedule</span>
                <span>Jul 26, 2021</span>
            </div>

            <div class="d-flex ">
                <span class="material-icons-round mr-3">bookmark</span>
                <span>Mobile App</span>
            </div>

          </v-row>

<!-- slide -->

           <v-row class="justify-center my-12" >
               <v-col cols="10" md="5" >
                    <v-carousel 
                    reverse-transition="fade-transition" 
                    transition="fade-transition"
                    cycle="true"
                    class="rounded-lg"
                    height="290"
                    >
                        <slider :images="['1.jpg','2.jpg','3.jpg']"/>

                    </v-carousel>
               </v-col>
           </v-row>

<v-divider class="mt-8 mb-4"></v-divider>

            <v-row class="mt-5 md-10 project-about" align="center">
              <v-col md="7">
                    <h2>About Project</h2> 
                <p class="text-justify mt-4" >
                    Morbi mattis ullamcorper velit. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Fusce convallis metus id felis luctus adipiscing. Aenean massa. Vestibulum purus quam, scelerisque ut, mollis sed, nonummy id, metus.
                    Nulla consequat massa quis enim. Praesent venenatis metus at tortor pulvinar varius. Donec venenatis vulputate lorem. Phasellus accumsan cursus velit. Pellentesque ut neque.<span v-if="readmore"></span>
                <span v-else>...</span>
                </p>

                <p v-show="readmore" class="text-justify mt-4">
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias similique reiciendis maxime nisi distinctio reprehenderit nobis, cum rerum odio voluptate.
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias similique reiciendis maxime nisi distinctio reprehenderit nobis, cum rerum odio voluptate.
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestias similique reiciendis maxime nisi distinctio reprehenderit nobis, cum rerum odio voluptate.
                </p>

                    <v-btn @click="readmore =! readmore" 
                    small  color="primary">
                      <span v-if="readmore">Read Less</span>
                      <span v-else>Read More</span>
                    </v-btn>
                
                    
              </v-col>

              <v-col md="5" align="center">
                   <v-row justify="center">
                     <h2>Tools & Technologies</h2> 
                   </v-row>
                  <v-row  class="d-flex skill-icon mt-4" justify="center" >
                    <skillIcon image="html" tooltipText="Html" />
                    <skillIcon image="css" tooltipText="Css" />
                    <skillIcon image="js" tooltipText="JavaScript" />
                    <skillIcon image="vuetify" tooltipText="Vuetify Js" />
                    <skillIcon image="vue" tooltipText="Vue Js" />
                    <skillIcon image="nodejs" tooltipText="Node Js" />
                  </v-row>
              </v-col>
            </v-row>



             <v-row class="mt-5" >
               <v-row class="my-6 mdAndsmCenter">
                 <h2>Related Projects</h2>
               </v-row>

                <v-row  class="mb-16 d-flex flex-wrap justify-center" >
                    <relatedProject link="Choveen" image="4.jpg" />
                    <relatedProject link="FishLand" image="3.jpg" />
                    <relatedProject link="Shex-Yusuf" image="1.jpg" />
                    <relatedProject link="Shex-Hallo" image="2.jpg" />
               </v-row>
             </v-row>



          </v-container>
    </div>
</template>

<script>
import skillIcon from "../../components/skill-icon.vue";
import slider from '../../components/project-slider.vue';
import relatedProject from '../../components/project_related_image.vue';
    export default {
        components: {
            slider,skillIcon,relatedProject
        },
        data() {
            return {
                  readmore:false,
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>
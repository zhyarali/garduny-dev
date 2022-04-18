<template>
  <div>
      
<!-- need a product -->

  <v-row id="about" align="center" md="10" class="my-16 d-flex justify-space-around hero-section">
   
    <v-col md="6" align="center" data-aos="fade-up"
     data-aos-anchor-placement="center-bottom" data-aos-duration="2000"> 
  <v-img
    tile
    lazy-src="need_app.svg"
    max-width="450"
    src="need_app.svg"
    class="mr-auto"
  ></v-img>
 </v-col>
   
   
    <v-col md="6" align="center" data-aos="fade-up"
     data-aos-anchor-placement="center-bottom" data-aos-duration="2000">
      
<v-row color="dark">
  <v-card
    class="mx-auto" 
    style="background:none !important"
    elevation="0"
    align="left"
  >
   
    <v-card-text class="pb-0 text-h5 font-weight-bold text-mode">
      Need a Creative Product?<br>I can Help You!
    </v-card-text>

    <v-card-subtitle class="text--primary">
      <div style="color:#919191" class="text-justify">
        Hi! I’m Muhammad Garduny, 
        I Am a Full-stack Developer With Alot Experience From Backend and Frontend of the Applications in Software Development and Working as Fullstack Web Developer Working With Php and Javascript & Typescript and Mvc Model and I Have Own Mvc Framework With Php 8 and Can Work With Alot of Php Frameworks Like: {symphony,falcon,codeingniter,slime,laravel,cakephp,etc} and Can Work With Alot Javascript Frameworks Like Vue and React and Libraries 
        And Fullstack Laravel & Livewire|vue|react and Can Work With Multiple Sql and Nosql Databases:{mysql,postgresql,sqllite,mongodb} 
        With Both {mevn-mern} Stack and 
        Now I Am a Freelancer With Remote Job but Before
        I Have Worked in (Emico Jumla and Bigpower Company Like It Administration and I Have Remotly Worked as It Manager From {myteacher} Website Until Now and Creator of Choveen Website  It Is a Business Website)
        So I Have Power for Facilitate Any Stack and Any Project to Learn or Teach or Working on It .
      </div>
    </v-card-subtitle>

    <v-card-actions>
      <v-btn class="primary" @click="hire_me=true" text>Hire Me</v-btn>
      <v-btn href="cv.pdf" Download class="secondary" text>Download Cv</v-btn>
    </v-card-actions>
  </v-card>

  </v-row>
       
    </v-col> 
  </v-row>




  
<!-- my skill -->

  <v-row  align="center" md="10" class="my-16 hero-section">
   

    <v-col md="6" align="center" data-aos="fade-up"
     data-aos-anchor-placement="center-bottom" data-aos-duration="2000">
      
  <v-row color="dark" class="skill-text">
  <v-card
    class=" card-skill-text"
    max-width="400"
    style="background:none !important"
    elevation="0"
    align="left"
  >
   
    <v-card-text class="pb-0 text-h4 font-weight-bold text-mode">
      What My Programming<br>Skills Included?
    </v-card-text>

    <v-card-subtitle class="text--primary">
      <div style="color:#919191">
I develop , intuitive and responsive user interface that helps users get things done with less effort and time with those technologies.      </div>
    </v-card-subtitle>

  </v-card>
        </v-row>
       
    </v-col> 


  <v-col md="6" align="right" data-aos="fade-up"> 
      <v-row class="d-flex skill-icon" justify="center" >
          <skillIcon image="html" tooltipText="Html" />
          <skillIcon image="css" tooltipText="Css" />
          <skillIcon image="js" tooltipText="JavaScript" />
          <skillIcon image="bootstrap" tooltipText="Bootstrap" />
          <skillIcon image="vuetify" tooltipText="Vuetify Js" />
          <skillIcon image="vue" tooltipText="Vue Js" />
          <skillIcon image="react" tooltipText="React Js" />
          <skillIcon image="nuxt" tooltipText="Nuxt Js" />
          <skillIcon image="nodejs" tooltipText="Node Js" />
          <skillIcon image="php" tooltipText="PHP" />
          <skillIcon image="laravel" tooltipText="Laravel" />
          <skillIcon image="codeigniter" tooltipText="Codeigniter" />
          <skillIcon image="api" tooltipText="RestFull Api" />
          <skillIcon image="git" tooltipText="Git" />
          <skillIcon image="github" tooltipText="GitHub" />
          <skillIcon image="firebase" tooltipText="Firebase" />
          <skillIcon image="mysql" tooltipText="MySQL" />
          <skillIcon image="mongodb" tooltipText="Mongo DB" />
         
      </v-row>
 </v-col>

  </v-row>


  
<v-dialog
        v-model="hire_me"
        max-width="500px"
      >

      <v-spacer></v-spacer>
        <v-card align="center">
          <v-card-title class="justify-center">
            <span>Have You Any Project? Please Drop a Message</span>
          </v-card-title>

              <v-divider
                class=""
              ></v-divider>
              <br>
          <v-card-text>
            <v-row
              align="center"
              justify="space-around"
            >
             <v-btn fab elevation="0" target="_blank" href="https://www.facebook.com/mohammad.garduny" style="background:none !important" dark>
               <v-img max-width="40"  src="facebook.svg"></v-img>
             </v-btn>
             <v-btn fab elevation="0" target="_blank" href="https://www.linkedin.com/in/garduny/" style="background:none !important"   dark>
               <v-img max-width="40" src="linkedn.svg"></v-img>
             </v-btn>
             <v-btn fab elevation="0" target="_blank" href="https://t.me/garduny" style="background:none !important" dark>
               <v-img max-width="40" src="telegram.svg"></v-img>
             </v-btn>

            </v-row>
          </v-card-text>
          <v-spacer></v-spacer>
          <v-spacer></v-spacer>
        </v-card>
      </v-dialog>

  </div>
</template>

<script>
import skillIcon from "../components/skill-icon.vue";
export default {
  name: 'AboutPage',
  components:{
    skillIcon,
  },
  data() {
    return {
      hire_me:false,
    }
  },
}
</script>



<style>
@media only screen and (max-width: 768px) {
  .skill-text{
    justify-content:center !important; 
  }
}
</style>
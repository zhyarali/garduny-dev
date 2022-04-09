<template>
<div>

  <v-row  align="center" md="10" class="my-10 d-flex justify-space-around hero-section">
    <v-col  md="4" align="center">
      
          <v-card
    class="mx-auto"
    max-width="400"
    style="background:none !important"
    elevation="0"
    align="center"
  >
   
    <v-card-text class="pb-0 text-h5 font-weight-bold text-mode">
      Hi, Iam Muhammed
    </v-card-text>

    <v-card-subtitle class="text--primary">
      <div style="color:#919191">
        A Full-Stack Developer
      </div>
    </v-card-subtitle>

    <v-card-actions>
      <v-btn href="cv.pdf" Download class="primary ma-auto" text>Download Cv</v-btn>
    </v-card-actions>
  </v-card>

    </v-col> 

 <v-col md="8" align="center"> 
  <v-img
    tile
    lazy-src="dev.svg"
    max-width="520"
    src="dev.svg"
  ></v-img>
 </v-col> 
  </v-row>


<!-- need a product -->

  <v-row id="about" align="center" md="10" class="my-16 d-flex justify-space-around hero-section">
   
    <v-col md="6" align="center" data-aos="fade-up"
     data-aos-anchor-placement="center-bottom" data-aos-duration="2000"> 
  <v-img
    tile
    lazy-src="need_app.svg"
    max-width="450"
    src="need_app.svg"
  ></v-img>
 </v-col>
   
   
    <v-col md="6" align="center" data-aos="fade-up"
     data-aos-anchor-placement="center-bottom" data-aos-duration="2000">
      
        <v-row color="dark">
  <v-card
    class="mx-auto"
    max-width="400"
    style="background:none !important"
    elevation="0"
    align="left"
  >
   
    <v-card-text class="pb-0 text-h5 font-weight-bold text-mode">
      Need a Creative Product?<br>I can Help You!
    </v-card-text>

    <v-card-subtitle class="text--primary">
      <div style="color:#919191">
        Hi! I’m Muhammad Garduny, and I’m a developer who has passion for building clean web applications with intuitive functionality. I enjoy the process of turning ideas into reality using creative solutions. I’m always curious about learning new skills, tools, and concepts. In addition to working on various solo full stack projects, I have worked with creative teams, which involves daily stand-ups and communications, source control, and project management.
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
      
        <v-row color="dark">
  <v-card
    class="mx-auto card-skill-text"
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


<!-- projects -->
<v-row class="justify-center mt-16" data-aos="zoom-in" data-aos-duration="2000">
   <h1>See My Works Which
Will Amaze You!</h1>
 </v-row>

<v-row class="justify-center mb-10 mt-10 flex-wrap">
          <projectCard link="health" image="1.jpg" title="Health Management System hhhhhhh" type="Mobile App"/>
</v-row>    

  <v-row  class="justify-center mb-16">
    <v-btn  color="primary">See More</v-btn>
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
             <v-btn fab elevation="0" style="background:none !important" dark>
               <v-img max-width="40" src="facebook.svg"></v-img>
             </v-btn>
             <v-btn fab elevation="0" style="background:none !important"   dark>
               <v-img max-width="40" src="linkedn.svg"></v-img>
             </v-btn>
             <v-btn fab elevation="0" style="background:none !important" dark>
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
import projectCard from "../components/project-card.vue";
export default {
  name: 'IndexPage',
  components:{
    skillIcon,
    projectCard
  },
  data() {
    return {
      hire_me:false,
    }
  },
}
</script>

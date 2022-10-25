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
      Hi, Iam Zhyar
    </v-card-text>

    <v-card-subtitle class="text--primary">
      <div style="color:#919191">
        A Senior Software Developer
      </div>
    </v-card-subtitle>

    <v-card-actions>
      <v-btn href="ZhyarAliMahmoodResume.pdf" Download class="primary ma-auto" text>Download Cv</v-btn>
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



  </div>
</template>



<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      
    }
  },
}
</script>

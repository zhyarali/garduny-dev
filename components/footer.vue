<template>
    <div>
    
    <v-footer class="bg-mode">
      <v-card
        flat
        tile
        width="100%"
        class="bg-mode text-center"
      >

        <v-card-title class="justify-center">
            Follow Me
        </v-card-title>

        <v-card-text>

          <v-btn class="mx-4" target="_blank" href="https://www.facebook.com/Zhyar.Ali.Mahmood/" icon>
           <v-img max-width="30"
             src="facebook.svg">
             </v-img>
          </v-btn>
          <v-btn class="mx-4" target="_blank" href="https://www.linkedin.com/in/zhyar-ali-mahmood-5723041bb/" icon>
           <v-img max-width="30"
             src="linkedn.svg">
             </v-img>
          </v-btn>
          <v-btn class="mx-4" target="_blank" href="https://t.me/zhyaralimahmud" icon>
           <v-img max-width="30"
             src="telegram.svg">
             </v-img>
          </v-btn>

              <v-btn fab elevation="0" target="_blank" href="viber://chat?number=07501520479" style="background:none !important" icon>
               <v-img max-width="30" src="viber.svg"></v-img>
             </v-btn>
             <v-btn fab elevation="0" target="_blank" href="https://api.whatsapp.com/send?phone=07501520479" style="background:none !important" icon>
               <v-img max-width="30" src="whatsapp.svg"></v-img>
             </v-btn>
      
        </v-card-text>

        <v-divider></v-divider>

        <v-card-text class="text-mode footer-text">
          {{ new Date().getFullYear() }} — <strong>Zhyar </strong>
        </v-card-text>
      </v-card>
    </v-footer>

    </div>
</template>

<script>
    export default {
        data() {
            return {
     
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>

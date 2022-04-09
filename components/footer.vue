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
          <v-btn
            v-for="image in images"
            :key="image"
            class="mx-4"
            icon
          >
           <v-img
             max-width="30"
             :src="image"
           ></v-img>
          </v-btn>
        </v-card-text>

        <v-divider></v-divider>

        <v-card-text class="text-mode">
          {{ new Date().getFullYear() }} — <strong>Garduny Dev</strong>
        </v-card-text>
      </v-card>
    </v-footer>

    </div>
</template>

<script>
    export default {
        data() {
            return {
                 images: [
        'facebook.svg',
        'linkedn.svg',
        'telegram.svg',
      ],
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>
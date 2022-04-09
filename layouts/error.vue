<template>
  <v-app dark>
     <v-row align="center" class="justify-center mb-16">
       <v-col cols="12" md="12" align="center">

         <div class="d-flex justify-center">
                <h1 class="textSize" v-if="error.statusCode === 404">
      {{ pageNotFound }}
    </h1>
    <h1 class="textSize" v-else>
      {{ otherError }}
    </h1>
    <div class="Verticalline mx-4">|</div>
    <NuxtLink class="text-decoration-none warning--text font-weight-bold" to="/">
      <p class="textSize">Home page</p>
    </NuxtLink>
         </div>
      
       </v-col>
     </v-row>
  </v-app>
</template>

<script>
export default {
  name: 'EmptyLayout',
  layout: 'empty',
  props: {
    error: {
      type: Object,
      default: null
    }
  },
  data () {
    return {
      pageNotFound: '404 Not Found',
      otherError: 'An error occurred'
    }
  },
  head () {
    const title =
      this.error.statusCode === 404 ? this.pageNotFound : this.otherError
    return {
      title
    }
  }
}
</script>

<style scoped>
.textSize {
  font-size: 20px;
}

.Verticalline{
  width:3px;
  height:25px;
  background-color:aliceblue !important;
}
</style>

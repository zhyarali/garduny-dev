<template>
  <div>
    <v-carousel-item 
      v-for="(item,i) in images"
      :key="i"
      :src="'/img/'+item"
    >
     
    </v-carousel-item>
</div>
</template>

<script>
  export default {
      props:['images'],
    data: () => ({
      model: 0,
      colors: [
        'primary',
        'secondary',
        'yellow darken-2',
        'red',
        'orange',
      ],
    }),
  }
</script>

<style lang="scss" scoped>

</style>
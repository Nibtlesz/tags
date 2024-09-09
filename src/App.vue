<script>
  import InputTag from './components/inputTag.vue';

  export default{
    components:{
      InputTag,
    },
    methods: {
      handleOnTagsChange(tags){
        console.log(tags);
      }
    }
  }
</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <InputTag @onTagsChange="handleOnTagsChange"/>
</template>

<style scoped>

</style>

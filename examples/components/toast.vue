<template>
  <div>
    toast test

    <toast></toast>

    <button @click="toastshow('i am toast0')">toast show 'i am toast0'</button>
    <button @click="toastshow('i am toast1')">toast show 'i am toast1'</button>

  </div>
</template>

<script>

  import Vue from 'vue';
  import toast from '../../src/components/toast/index'

  Vue.use(toast);

  export default {
    name: 'HelloWorld',
    data() {
      return {}
    },
    methods:{
      toastshow(str){
        this.$toast(str)
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

<template>
  <div>
    toast test

    <!--<Toast class="test"></Toast>-->

    <div class="testnum">12345</div>

    <!--<button @click="toastshow('i am toast0')">toast show 'i am toast0'</button>-->
    <!--<button @click="toastshow('i am toast1')">toast show 'i am toast1'</button>-->

    <Toast></Toast>

  </div>
</template>

<script>
  // import Vue from 'vue'
  // import Toast from '../../components/toast/index'
  // Vue.use(Toast)

  export default {
    name: 'toast_name',
    // components:[Toast},
    data() {
      return {}
    },
    methods: {
      toastshow(str) {
        this.$toast(str)
      }
    },
    mounted(){
      this.$toast('12345')
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

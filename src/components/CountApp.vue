<template>
  <p>{{ num }}</p>
  <button v-on:click="up" class="btn btn-primary">Up</button>　
  <button v-on:click="reset" class="btn btn-dark">Reset</button>

</template>

<script>

export default {
  data() {
    return {
      num: 0
    }
  },
  methods:{
    up(){
      this.num++
    },
    reset(){
      this.num = 0
    }
  }

}
</script>

<style scoped>
p{
  font-size: 1000%;
}

</style>

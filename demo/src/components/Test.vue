<template>
  <div>
    Just a test page.
    <div>
      <router-link to="/">Home</router-link>
    </div>
    <div>
      <h2>{{mode}}</h2>
    </div>
    <div><span>{{count}}</span></div>
    <div><button @click="numcount">+1</button></div>
  </div>
</template>
<script>
export default {
  data () {
    return {
      count: 2,
      mode: process.env.VUE_ENV === 'server' ? 'server' : 'client'
    }
  },
  methods: {
    numcount () {
      console.log('++++++++')
      this.count++
    }
  }
}
</script>

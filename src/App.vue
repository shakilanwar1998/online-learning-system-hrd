
<template>
  <div id="app">
    {{fullName}}
    <strong>Followers : </strong> {{ followers }}
    <button @click="followUser">Follow</button>
  </div>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      followers : 0,
      user : {
        firstName : "Shakil",
        lastName : "Anwar",
        email : "shakilanwar1998@gmail.com",
        isAdmin : true
      }
    }
  },
  computed : {
    fullName(){
      return `${this.user.firstName} ${this.user.lastName}`
    }
  },
  methods : {
    followUser(){
      this.followers++;
    }
  },
  mounted () {
      this.followUser();
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

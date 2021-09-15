<template>
    <div class="blog-navi" >
        <v-row align="center" justify="space-around">
            <v-btn text class="navi-button" @click="goToHome()">Home</v-btn>
            <v-btn text class="navi-button" @click="debug()">Technology</v-btn>
            <v-btn text class="navi-button">Life</v-btn>
            <v-btn text class="navi-button">Gallery</v-btn>
            <v-btn text class="navi-button">About</v-btn>
        </v-row>
    </div>
</template>

<script>
export default {
  name: 'blogNavi',
  methods: {
    goToHome() {
      this.$router.push('/home')
    },
    debug() {
        console.log("clicked")
    }
  }
}
</script>

<style scoped>
.blog-navi{
    text-align: center;
    width: 35%;
    margin-top: 20px;
}
.navi-button{
    /* font-family: 'Raleway'; */
    font-family: 'Annie Use Your Telescope';
    font-size: 28px;
    margin-left: 12px;
}
</style>

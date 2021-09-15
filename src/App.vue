<template>
  <div>
    <blogHeader></blogHeader>
    <blogNavi></blogNavi>
   </div> 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import blogHeader from './components/header.vue'
import blogNavi from './components/navigation.vue'

export default {
  name: 'App',
  components: {
    blogHeader,
    blogNavi
  }
}
</script>

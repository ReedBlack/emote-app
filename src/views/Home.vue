<template>
<div>
  <div class="home">
    <Header /> 
    <Navigate />
  </div>
    <BubbleData />
    </div>
</template>

<script>
import Header from "@/components/Header"
import Navigate from "@/components/Navigate"
import BubbleData from "@/components/BubbleData"


export default {
  name: 'home',
  components: {
    Header,
    Navigate,
    BubbleData
  }
  
}
</script>

<style>
  .home {
    display: flex;
    flex-direction: row;
    justify-content: space-between;  
  }
</style>

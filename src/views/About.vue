<template>
  <div class="about">
    <div class="home">
      <Header /> 
      <Navigate />
    </div>
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import Header from "@/components/Header"
import Navigate from "@/components/Navigate"
export default {
  components: {
    Navigate,
    Header
  }
}
</script>

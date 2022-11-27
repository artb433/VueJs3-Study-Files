<template>
  <div class="container mt-3">
   <div class="grid">
    <div class="row">
     <div class="col">
      <p class="h3 text-success fw-bold">
       App Component
      </p>
      <p class="fw-bold fs-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas nisi architecto repellendus blanditiis in magnam laudantium ut saepe harum sit, natus illum minima doloremque amet perspiciatis asperiores praesentium molestias velit!</p>
     </div>
    </div>
   </div>
 
   <!-- <Customer name="Rajan" age="25" /> -->
   <Employee/>
   <Counter/>
   <Greeting/>
   <Register/> 
   <Customer/>
 
   
  </div>
  
 </template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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

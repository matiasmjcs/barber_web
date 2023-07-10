<script setup lang="ts">
import {ref} from 'vue'
const state = ref(false)

</script>
<template>
  <section>
  <article class="article-col">
    <button class="select" v-if="state == false" @click="state = false">Fade</button>
    <button v-if="state == true" @click="state = false">Fade</button>
    <button class="select" v-if="state == true" @click="state = true">Clasicos</button>
    <button v-if="state == false"  @click="state = true">Clasicos</button>
  </article>
    
    <article class="article-clasicos" v-if="state == true">
      <img src="../../assets/clasico1.webp"/>
      <img src="../../assets/clasico2.webp"/>
      <img src="../../assets/clasico3.webp"/>

    </article> 
    <article class="article-fade" v-if="state == false">
      <img src="../../assets/fade5.webp"/>
      <img src="../../assets/fade1.webp"/>
      <img src="../../assets/fade2.webp"/>
    </article>
    
  </section>
</template>

<style scoped>

section {
  display: grid;
  justify-items: center;
}

.article-col {
  width: 50%;
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-items: center;
  justify-content: center;
  align-items: center;
}

.article-col button{
  width: 130px;
  height: 40px;
  padding: 10px;
  border-radius: 4px;
  margin: 10px;
  font-weight: bold;
  font-family: monospace;
  font-size: medium;
  border: 1px solid black;
  transition: all .3s;
}

.select {
  background-color: black;
  color: white;
}

.article-fade, .article-clasicos {
  margin: 20px;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  grid-gap: 20px;
  justify-content: center;
  justify-items: center;
  transition: all .3s linear;
}

img {
  width: 250px;
  height: 250px;
  box-shadow: 0px 0px 2px 0px black;
  cursor: pointer;
  transition: all .3s;
  border-radius: 4px;
  
}
img:hover {
  transform: scale(1.1);
}
@media (min-width: 992px) {
  .article-fade, .article-clasicos {
    grid-template-columns: repeat(3, 1fr);
  }
  img {
   width:300px;
   height: 300px;
  }
}
</style>
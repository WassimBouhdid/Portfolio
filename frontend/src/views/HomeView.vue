<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/photoWassim.jpg" class="img-fluid" style="width:200px; border-radius:50px">
    <div>étudiant en technologie de l'informatique à la haute école de l'EPHEC à Louvain-La Neuve</div>
    <HelloWorld msg="Bienvenu sur le portfolio de Bouhdid Wassim"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

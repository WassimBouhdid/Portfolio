<template>
  <div class="home container">
    <HelloWorld msg="Bienvenue sur le portfolio de Bouhdid Wassim" />

    <img alt="Vue logo" src="../assets/photoWassim.jpg" class="img-fluid" style="width:200px; border-radius:50px">
    <div>
      <div>
        <h2>Présentation</h2>
        <p> Bonjour,je m'appelle Wassim et je suis en dernière année de Bac à la Haute école de l'EPHEC à Louvain-La
          Neuve</p>
        
      </div>
      <div id="CV">
        <h2> Mon CV </h2>
        <a target="_blank" href=".\BouhdidWassim-CV-EPHEC.pdf" title="test" download="CV wassim"><button type="button"
            class="btn btn-success">Télécharger mon CV</button></a>
      </div>
      <div id="heures">
        <h1>Portfolio</h1>
        <div class="row">
          <h3>Année 2021</h3>
          <div class="col">
            <h4> Tutorat </h4>
            Temps total : 25h
            Temps valorisé : 10h
            <p> Tutorat tous les samedis après-midi en développement web 1 théorie et pratique à un élève de première pendant tout le premier quadrimèstre </p>
          </div>
          <div class="col">
            <h4> Formation PHP </h4>
            <img src=".\..\assets\cert-1059-19748106.jpg" class="img-fluid" >
            Temps total : 10h
            Temps valorisé : 10h
            <p> Formation PHP sur la plateforme Sololearn </p>
          </div>
          <div class="col">
            <h4> Travail étudiant chez Spie au campus Solvay </h4>
            <img src=".\..\assets\spie.png" class="img-fluid" >
            Temps total : 24h
            Temps valorisé : 0h
            <p> Installation d'écran et de docking stations </p>
          </div>
        </div>
        <div class="row">
          <div class="col">
            <h4> Formation Fullstack </h4>
            <img src=".\..\assets\Fullstack.png" class="img-fluid" >
            Temps total : 10h
            Temps valorisé : 10h
            
            <p> Formation Fullstack ( Nodejs, express, MongoDB,) sur le site OpenClassroom </p>
          </div>
          <div class="col">
            <h4> Formation Angular </h4>
            <img src=".\..\assets\angular.png" class="img-fluid" >
            Temps total : 10h
            Temps valorisé : 10h
            <p> Formation Angular sur le site OpenClassroom </p>
          </div>
        </div>
        <div class="row">
          <h3>Année 2022</h3>
          <div class="col">
            <h4> DevDay</h4>
            <img src=".\..\assets\dev_day.jpg" class="img-fluid" >
            Temps valorisé : 8h
            <p> Suivi de 4 conférences IT de 2h au cinéma de Louvain-la-Neuve à l'occasion du Dev Day </p>
            </div>
          <div class="col">
            <h4> Travail étudiant chez mastercard Waterloo </h4>
            <img src=".\..\assets\mastercard1.jpg" class="img-fluid" >
            Temps valorisé : 10h
            <p>Montage de bureau et d'écran pour leurs nouveaux locaux à Waterloo</p>
          </div>
          <div class="col">
            <h4> Formation développement Android </h4>
            <img src=".\..\assets\devAndroid.png" class="img-fluid" >
            Temps valorisé : 10h
            <p>Formation au développement Android sur le site OpenClassroom</p>
          </div>
          
        </div>
      </div>
    </div>

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
<style>
  #CV {
    padding: 300px;
  }
</style>
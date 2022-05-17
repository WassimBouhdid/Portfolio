<template>
  <div class="home container">
    <HelloWorld msg="Bienvenu sur le portfolio de Bouhdid Wassim" />

    <img alt="Vue logo" src="../assets/photoWassim.jpg" class="img-fluid" style="width:200px; border-radius:50px">
    <div>
      <div>
        <h2>Présentation</h2>
        <p> Bonjour Je m'appelle Wassim et je suis en dernière année de Bac à la Hhaute école de l'EPHEC à Louvain-La
          Neuve</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ex porro illum delectus laudantium error! Culpa
          sint nisi sapiente expedita esse excepturi consequatur eaque recusandae, eligendi nostrum sit quaerat optio
          eveniet.</p>
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam maiores iure excepturi. Nostrum nam tenetur
          numquam iste, quas provident minus ducimus quod, quaerat dicta perferendis necessitatibus veniam accusamus
          asperiores expedita.</p>
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam maiores iure excepturi. Nostrum nam tenetur
          numquam iste, quas provident minus ducimus quod, quaerat dicta perferendis necessitatibus veniam accusamus
          asperiores expedita.</p>
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam maiores iure excepturi. Nostrum nam tenetur
          numquam iste, quas provident minus ducimus quod, quaerat dicta perferendis necessitatibus veniam accusamus
          asperiores expedita.</p>
        <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam maiores iure excepturi. Nostrum nam tenetur
          numquam iste, quas provident minus ducimus quod, quaerat dicta perferendis necessitatibus veniam accusamus
          asperiores expedita.</p>
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
            <p> Tutorat tout les samedi après midi en dévellopement web 1 théorie et pratique à un élève de première pendant tout le premier quadrimèstre </p>
          </div>
          <div class="col">
            <h4> Formation PHP </h4>
            <img src=".\..\assets\cert-1059-19748106.jpg" class="img-fluid" >
            Temps total : 10h
            Temps valorisé : 10h
            <p> Formation PHP sur la plateforme Sololearn </p>
          </div>
          <div class="col">
            <h4> Travail étudiant chez Spie au campus Solvay Ixelle </h4>
            <img src=".\..\assets\spie.png" class="img-fluid" >
            Temps total : 24h
            Temps valorisé : 0h
            <p> Installation d'écran et de docking station </p>
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
            <h4> Dev Day</h4>
            <img src=".\..\assets\dev_day.jpg" class="img-fluid" >
            Temps valorisé : 8h
            <p> Suivis de 4 conférence IT de 2h au cinéma de Louvain-La Neuve à l'ocasion du Dev Day </p>
            </div>
          <div class="col">
            <h4> Travail étudiant chez mastercard Waterloo </h4>
            <img src=".\..\assets\mastercard1.jpg" class="img-fluid" >
            Temps valorisé : 10h
            <p>Montage de bureau et d'écran pour leur nouveau Locaux à Waterloo</p>
          </div>
          <div class="col">
            <h4> Formation développement Android </h4>
            <img src=".\..\assets\devAndroid.png" class="img-fluid" >
            Temps valorisé : 10h
            <p>Formation au dévellopement Android sur le site OpenClassroom</p>
          </div>
          
        </div>
      </div>
      <div id="competences">
        <h3>Frontend</h3>
        <h3>Backend</h3>
        <h3> dévellopement applicatif </h3>
        <h3> Électronique </h3>
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
    padding: 50px;
  }
</style>
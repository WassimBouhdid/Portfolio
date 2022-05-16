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
        <a target="_blank" href="./BouhdidWassim-CV-EPHEC.pdf" title="" download><button type="button"
            class="btn btn-success">Télécharger mon CV</button></a>
      </div>
      <div id="heures">
        <p>
          <a class="btn btn-primary" data-bs-toggle="collapse" href="#multiCollapseExample1" role="button"
            aria-expanded="false" aria-controls="multiCollapseExample1">Année 2020</a>
          <a class="btn btn-primary" data-bs-toggle="collapse" href="#multiCollapseExample2" role="button"
            aria-expanded="false" aria-controls="multiCollapseExample2">Année 2021</a>
          <a class="btn btn-primary" data-bs-toggle="collapse" href="#multiCollapseExample3" role="button"
            aria-expanded="false" aria-controls="multiCollapseExample3">Année 2022</a>
        </p>
        <div class="row">
          <div class="col">
            <div class="collapse multi-collapse" id="multiCollapseExample1">
              <div class="card card-body">
                Année 2020
              </div>
            </div>
          </div>
          <div class="col">
            <div class="collapse multi-collapse" id="multiCollapseExample2">
              <div class="card card-body">
                Année 2021
              </div>
            </div>
          </div>
          <div class="col">
            <div class="collapse multi-collapse" id="multiCollapseExample3">
              <div class="card card-body">
                Année 2022
              </div>
            </div>
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
#CV{
  padding:50px;
}
</style>
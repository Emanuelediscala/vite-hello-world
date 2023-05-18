<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppHero",
}
</script>
<template>
<div class="p-5 text-center bg-image rounded-3" style="
    background-image: url('https://mdbcdn.b-cdn.net/img/new/slides/041.webp');
    height: 400px;
  ">
  <div class="mask" style="background-color: rgba(0, 0, 0, 0.6);">
    <div class="d-flex justify-content-center align-items-center h-100">
      <div class="text-white">
        <h1 class="mb-3">La Mia App con Vitae</h1>
        <h4 class="mb-3">Subscrition</h4>
        <a class="btn btn-outline-light btn-lg" href="#!" role="button">MORE DETAILS</a>
      </div>
    </div>
  </div>
</div>
</template>
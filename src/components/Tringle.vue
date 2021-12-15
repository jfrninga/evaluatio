<template>
  <div class="main-container">
    <div class="sub-container">
      <h3>Tringle Rail</h3>
      <div class="content-img">
      </div>
      <img src="assets/tringles-rail.jpg" alt="tringles" />
    </div>
    <div class="content">
      <div class="detail-produit">
        <h3>Personnalisez votre produit :</h3>
        <p>1. J'indique mes dimensions</p>
        <h4>Longueur du rail</h4>
        <input type="number" id="number" name="number" min="50" max="600" />
        <button>Valider</button>
      </div>
      <div class="detail-produit">
        <p>2. J'indique mon type de rail</p>
        <div id="field" class="card-tringle">
          <img src="assets/1.png" alt="choix_1" />
          <img src="assets/2.png" alt="choix_2" />
        </div>
        <button>Valider</button>
      </div>
      <div class="detail-produit">
        <p>3. Je selectionne ma couleur</p>
        <div id="field" class="card-tringle">
          <img src="assets/blanc.png" alt="choix_1" />
          <img src="assets/noir.png" alt="choix_2" />
        </div>
        <button>Valider</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Tringle",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
  .main-container {
    display: flex;
    justify-content: space-evenly;
  }
</style>

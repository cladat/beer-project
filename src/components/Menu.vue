<template>
  <div class="container mt-2">
    <div class="btns my-3">
      <a href="#" class="btn btn-primary">Tout</a>
      <a href="#" class="btn btn-primary">Prix</a>
    </div>
    <div class="row">
      <div class="col-4">
        <div class="card">
          <img
            class="card-img-top"
            src="../../static/images/corbeau.jpg"
            height="100%"
            alt="Card image cap"
          >
          <div class="card-body">
            <h5 class="card-title">LA CORBEAU</h5>
            <div class="text-primary">
              <span>★</span>
              <span>★</span>
              <span>★</span>
            </div>
            <p class="card-text">
              La bière du Corbeau est une bière blonde trés gazeuse et avec une belle mousse
              persistante.Le nez propose des arômes de citron, de végétal et de caramel.la ...
            </p>
            <div class="d-flex justify-content-between">
              <span class="text-primary">
                <strong>3.10 €</strong>
              </span>
              <a href="#" class="btn btn-primary">Ajouter</a>
              <span>5 en stock</span>
            </div>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card">
          <img
            class="card-img-top"
            src="../../static/images/jeackhammer.jpg"
            height="100%"
            alt="Card image cap"
          >
          <div class="card-body">
            <h5 class="card-title">JACK HAMMER</h5>
            <div class="text-primary">
              <span>★</span>
              <span>★</span>
              <span>★</span>
              <span>★</span>
            </div>
            <p class="card-text">
              Selon la rumeur, la Jack Hammer serait une bière tellement houblonnée que l'on y
              retrouverait plus d'amertume que le palais humain ne puisse détecter.
            </p>
            <div class="d-flex justify-content-between">
              <span class="text-primary">
                <strong>3.50 €</strong>
              </span>
              <a href="#" class="btn btn-primary">Ajouter</a>
              <span>5 en stock</span>
            </div>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card bg-warning">
          <img
            class="card-img-top"
            src="../../static/images/queuedecharrue.jpg"
            height="100%"
            alt="Card image cap"
          >
          <div class="card-body">
            <h5 class="card-title">QUEUE DE CHARRUE</h5>
            <div class="text-primary">
              <span>★</span>
              <span>★</span>
              <span>★</span>
              <span>★</span>
              <span>★</span>
            </div>
            <p class="card-text">
              La Queue de Charrue est une famille de bières brassées pour la Brasserie Vanuxeem. La
              plus connue et typique est la Queue de Charrue brune. Son nom ...
            </p>
            <div class="d-flex justify-content-between">
              <span class="text-primary">
                <strong>3.70 €</strong>
              </span>
              <a href="#" class="btn btn-primary">Ajouter</a>
              <span>1 en stock</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  data() {
    return {
      products: []
    }
  }
}
</script>

<style lang="sass">

</style>

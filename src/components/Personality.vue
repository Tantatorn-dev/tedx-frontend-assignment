<template>
  <div class>
    <h1 id="topo" class="is-size-3">
      Dogs have these 5 major personality types
    </h1>
    <nav class="level">
      <div class="level-item has-text-centered">
        <div>
          <img src="../assets/icon-1.png" />
          <p class="subtitle">Confident</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <img src="../assets/icon-2.png" />
          <p class="subtitle">Shy</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <img src="../assets/icon-3.png" />
          <p class="subtitle">Independent</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <img src="../assets/icon-4.png" />
          <p class="subtitle">Laidback</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <img src="../assets/icon-5.png" />
          <p class="subtitle">Adaptable</p>
        </div>
      </div>
    </nav>
    <button id="learnmore-button" class="button is-primary">Learn More</button>
  </div>
</template>

<script>
export default {
  name: "Personality",
};
</script>

<style scoped>
#topo {
  margin: 40px;
}

#learnmore-button {
  margin-top: 20px;
  background-color: rgb(146, 194, 199);
  border-radius: 25px;
  margin-bottom: 40px;
}

nav {
    overflow: auto;
}

p {
    margin-top: 20px;
}
</style>

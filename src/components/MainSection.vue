<template>
  <div class="columns reverse-row-order">
    <div id="doggo-bg" class="crop column" :style="cssProps">
      <img id="doggo" src="../assets/hero.png" />
    </div>
    <div class="column">
      <h1 id="topo1" class="is-size-4 has-text-weight-semibold">
        What's meant to be will always find a way.
      </h1>
      <h1 id="topo2" class="is-size-6">
        PawsUp help you to find the best <br />
        partner for your dearest fluffy friend
      </h1>
      <button id="match-button" class="button is-primary">Find A Match</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainSection",
  data() {
    return {
      cssProps: {
        backgroundImage: `url(${require("@/assets/bgfoot.png")})`,
      },
    };
  },
};
</script>

<style scoped>
#topo1 {
  margin-inline: 100px;
  margin-bottom: 10px;
  margin-top: 100px;
}
#match-button {
  margin-top: 20px;
  background-color: palevioletred;
  border-radius: 25px;
}
.crop {
  height: 420px;
  overflow: hidden;
}

.crop #doggo {
  padding-top: 20px;
  height: 500px;
}

#doggo-bg {
  background-color: rgb(253, 230, 230);
  border-bottom-left-radius: 100px;
}

.reverse-row-order {
  flex-direction: row-reverse;
}

@media screen and (max-width:400px) {
    #topo1{
        margin-top: 0px;}
}

</style>

<template>
  <div class="typed">
    <vue-typed-js
      class="typeddd"
      :strings="['Asadbek Nosirjonov', 'Front-end']"
      :typeSpeed="90"
      :startDelay="1000"
      :backSpeed="20"
      :smartBackspace="true"
      :loop="true"
    >
      <h1 class="typing"></h1>
    </vue-typed-js>
  </div>
</template>

<script>
Vue.use(VueTypedJs);
import Vue from "vue";
import { VueTypedJs } from "vue-typed-js";
export default {
  components: {
    VueTypedJs,
  },
  data() {
    return {};
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.typed {
  width: 100vw;
  height: 100vw;
  background-image: url("../assets/Texture-wallpaper-HD-download-desktop.jpg");
  background-repeat: no-repeat;
}
.typing {
  text-align: center;
  padding-top: 20%;
  color: #fff;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: 700;
  font-size: 30px;
}
.typeddd {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>

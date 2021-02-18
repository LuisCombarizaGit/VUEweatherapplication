<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search.." />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      api_key: "98b5ba2ee69aa64434fb7d86727ae023",
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "montserrat", sans-serif;
}

#app {
  background-image: url("./background-img.jpg");
  background-size: cover;
  background-position: bottom;
}

main {
  min-height: 100vh;
  padding: 25px;
}
</style>

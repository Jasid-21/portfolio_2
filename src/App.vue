<template>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: $text;
}

* {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}

html, body {
  margin: 0;
  padding: 0;
  scroll-behavior: smooth;
}

html {
  font-size: 16px;
}

body {
  font-family: 'Poppins';
  font-weight: 400;
}

section, footer {
  padding: 100px var(--x_pad);
}

h1, h2, h3, h4, h5 {
  font-family: 'Poppins';
  font-weight: 700;
}

html {font-size: 100%;} /* 16px */

h1 {font-size: 4rem; /* 67.36px */}

h2 {font-size: 3rem; /* 50.56px */}

h3 {font-size: 2rem; /* 37.92px */}

h4 {font-size: 1.55rem; /* 28.48px */}

h5 {font-size: 1rem; /* 21.28px */}

small {font-size: 0.750rem; /* 12px */}

.link-item {
  cursor: pointer;
}

.section-title {
  text-align: center;
  margin: 0;
  margin-bottom: 4rem;
}

.important {
  color: $accent;
}
</style>

<template>
  <RouterView />
</template>

<style scped>
@font-face {
  font-family: 'DIN-Bold';
  src: url('/fonts/din-bold.otf');
}

body {
  min-width: 1450px;
}
@media (max-width: 768px) {
  body {
    min-width: auto;
  }
}

/* 字体名称 */
.ff-DIN-Bold {
  font-family: 'DIN-Bold';
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>

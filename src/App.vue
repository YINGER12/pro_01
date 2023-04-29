<template>
  <div id="app">
    <gButton></gButton>
  </div>
</template>

<script>
import gButton from './components/gButton.vue'

export default {
  name: 'App',
  components: {gButton},
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-size: var(--font-size);
}

#app{
  margin: 20px;
}

/* css变量声明 */
:root {
  --button-height:32px;
  --font-size:14px;
  --button-bg:white;
  --button-active-bg:#eee;
  --border-radius:4px;
  --color:#333;
  --border-color:#999;
  --border-color-hover:#666;
}
</style>

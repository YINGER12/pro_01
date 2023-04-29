<template>
  <div>
    <button>按钮</button>
  </div>
</template>

<script>
export default {
  name: "gButton",
};
</script>

<style scoped lang="less">
button {
  font-size: var(--font-size);
  height: var(--button-height);
  padding: 0 1em;
  border-radius: var(--border-radius);
  border: 1px solid var(--border-color);
  background: var(--button-bg);
}

button:hover {
  border-color: var(--border-color-hover);
}

// 点击后显示的背景色
button:active {
  background-color: var(--button-active-bg);
}

// button:focus {
//   outline: none;
// }  
</style>s

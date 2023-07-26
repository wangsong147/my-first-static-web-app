<template>
  <div>Hello {{ value }}
  <a href="https://app-demo44-230720094844.azurewebsites.net">点击发送</a>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World!"
    };
  }
};
</script>

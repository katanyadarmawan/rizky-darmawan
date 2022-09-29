<template>
  <!-- <div class="target" >1</div> -->
  <TemplateItem />
</template>

<style>
.target {
  width: 100px;
  height: 100px;
  margin: 300px auto 500px auto;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #43b883;
  border-radius: 10px;
  font-weight: bold;
}
</style>

<script>
import TemplateItem from "./template/template.vue";

export default {
  name: "App",
  components: {
    TemplateItem,
  },
};
</script>

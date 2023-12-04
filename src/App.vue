<template>
  <home-page />
</template>

<script setup>
import HomePage from "@/views/home-page.vue";
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

.icon {
  width: 20px;
  height: 20px;
}

h1 {
  color: rgb(0, 0, 0);
  text-align: left;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
  display: flex;
}

#basket {
  color: white;
  margin: 10px 10px 10px 10px;
  height: 30px;
  width: 30vh;
  border-radius: 30px;
  border-color: rgb(40, 0, 65);
  background-color: rgb(210, 139, 255);
  font-size: large;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}

#panel {
  background-color: aquamarine;
  margin-left: 20px;
  padding: 10px 15px;
  border-color: rgb(0, 191, 0);
  border-radius: 10px;
}

#panelDv {
  width: 200vh;
  height: 50px;
  margin-left: 10px;
  padding-top: 10px;
  /* background-image: url(panel.png); */
  border: 3px;
  border-color: blue;
  border-radius: 5px;
}

.card {
  width: max-content;
}

.blockPizza {
  /* margin-left: -130vh; */
  margin-top: 50px;
  display: block;
  text-align: center;
  /* font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; */
  font-size: 20px;
}

#blockPizza {
  padding: 5px 18px;
}

.specifications {
  margin-top: 10px;
  padding: 5px;
  background-color: #bebebe;
  display: flex;
  align-items: center;
  justify-content: space-between;
  list-style-type: none;
  border: 3px;
  border-radius: 10px 10px 0px 0px;
}

.size {
  padding: 5px;
  background-color: #bebebe;
  display: flex;
  align-items: center;
  justify-content: space-between;
  list-style-type: none;
  border: 3px;
  border-radius: 0px 0px 10px 10px;
}

.activeKey {
  width: 100%;
  height: 25px;
  align-items: center;
  padding: 0px 30px;
  display: flex;
  background-color: #ffffff;
  border: 10px;
  border-radius: 5px;
}

.key {
  align-items: center;
  padding: 0px 30px;
  display: flex;
  border: 3px;
}

.price-add {
  height: 30px;
  width: 50px;
  margin-top: 10px;
  margin-left: 10px;
  display: flex;
  white-space: nowrap;
  font-size: 25px;
}

.add {
  color: #fe5f1e;
  padding: 0px 15px;
  margin-left: 15px;
  border: 3px solid;
  background-color: #ffffff;
  border-color: #fe5f1e;
  border-radius: 10px;
  font-size: 18px;
}

.add:hover {
  background-color: #4e2087;
  color: white;
}

.quantity {
  padding: 0px 10px;
  color: white;
  background-color: #fe5f1e;
  border-radius: 10px;
}
</style>

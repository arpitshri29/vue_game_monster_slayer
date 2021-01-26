<template>
  <h1>Welcome to Monster Slayer!</h1>
  <BattleField />
</template>

<script>
import BattleField from "./components/BattleField";
import './styles.css'

export default {
  name: "App",
  components: {
    BattleField,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

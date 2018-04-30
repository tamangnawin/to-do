<template>
  <div id="app" class="container">
    <h1>
      मेरो टु-डु App
    </h1>
    <div class="list-box">
      <Todolist/>
    </div>
  </div>
</template>

<script>
import Todolist from './components/Todolist'

export default {
  name: 'App',
  components: {
    Todolist
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  background-color: #EEEBF2;
}
.container {
  max-width: 600px;
  margin: 0 auto;
  border: 1px solid rgba(0, 0, 0, 0.1);
  box-shadow: 1px 2px 2px rgba(0, 0, 0, 0.2);
  background-color: #F5F6F7;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}

h1{
    text-align: center;
    font-weight: 500;
    font-size: 35px;
    background-color: #4A83A6;
    padding: 17px;
    color: white;
    margin-top: 0;
}

.list-box {
  padding: 10px 35px;
}
</style>

<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-item">
        <div class="menu-text">
          Resume
        </div>
      </div>
      <div class="menu-item">
        <div class="menu-text">
          Gaming
        </div>
      </div>
      <div class="menu-item menu-center">
        Caleb Howe
      </div>
      <div class="menu-item">
        <div class="menu-text">
          YouTube
        </div>
      </div>
      <div class="menu-item">
        <div class="menu-text">
          About
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}

.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
  
}

.menu-item {
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-center{
  font-size: 40px;
}

.menu-text{
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}

.menu-text:hover {
  background: green;
}
</style>

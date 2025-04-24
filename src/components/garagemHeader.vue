<script setup>
</script>
<template>
     <header>
      <h1>Garagem</h1>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/Carros">Carros</router-link></li>
          <li><router-link to="/Clientes">Clientes</router-link></li>
          <li><router-link to="/Acessorio">Acessórios</router-link></li>
          <li><router-link to="/Categorias">Categorias</router-link></li>
          <li><router-link to="/Marcas">Marcas</router-link></li>
          <li><router-link to="/Cores">Cores</router-link></li>
          <li><router-link to="/Modelo">Modelos</router-link></li>
        </ul>
      </nav>
    </header>
</template>
<style scoped>
header {
  background-color: #333;
  color: white;
  padding: 10px;
  display: flex;
  gap: 20px;
  justify-content: space-between;
  align-items: center;
}
nav ul {
  list-style-type: none;
  padding: 0;
}
nav ul li {
  display: inline;
  margin-right: 20px;
}
nav ul li a {
  color: white;
  text-decoration: none;
}
nav ul li a:hover {
  text-decoration: underline;
}
nav ul li a.active {
  font-weight: bold;
}
nav ul li a.active:hover {
  text-decoration: none;
}

</style>
<template>
  <div class="home-page">
    <header class="header">
      <h1>Studio de Tatuagem</h1>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/portfolio">Portfólio</router-link></li>
          <li><router-link to="/contato">Contato</router-link></li>
        </ul>
      </nav>
    </header>

    <main class="content">
      <div class="content-inner">
        <h2>Bem-vindo ao nosso estúdio de tatuagem!</h2>
        <p>Oferecemos uma ampla variedade de estilos de tatuagem para atender às suas preferências e necessidades.</p>
        <p>Confira nosso portfólio para ver exemplos de nossos trabalhos.</p>
      </div>
    </main>

    <footer class="footer">
      <p>&copy; 2023 Studio de Tatuagem</p>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      // dados do componente, se necessário
    };
  }
};
</script>

<style>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
}

.home-page {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.header {
  background-color: #333;
  padding: 20px;
  color: #fff;
}

.header h1 {
  margin: 0;
}

.header nav ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

.header nav ul li {
  display: inline-block;
  margin-right: 10px;
}

.header nav ul li a {
  text-decoration: none;
  color: #fff;
}

.content {
  flex-grow: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

.content-inner {
  text-align: center;
}

.footer {
  background-color: #333;
  padding: 10px;
  color: #fff;
  text-align: center;
}
</style>

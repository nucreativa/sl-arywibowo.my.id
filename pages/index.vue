<template>
  <div id="wrapper">
    <div id="bg"></div>
    <div id="overlay"></div>
    <div id="main">
      <header id="header">
        <h1>Ary Wibowo</h1>
        <p>Technopreneur &nbsp;&bull;&nbsp; Founder of Nucreativa Digital Colony </p>
        <nav>
          <ul>
            <li>
              <a href="https://www.linkedin.com/in/nucreativa/" class="icon brands fa-linkedin">
                <span class="label">Linkedin</span>
              </a>
            </li>
            <li>
              <a href="https://github.com/nucreativa" class="icon brands fa-github">
                <span class="label">Github</span>
              </a>
            </li>
            <li>
              <a href="mailto:ary.wibowo@nucreativa.com" class="icon solid fa-envelope">
                <span class="label">Email</span>
              </a>
            </li>
          </ul>
        </nav>
      </header>

      <!-- Footer -->
      <footer id="footer">
        <span class="copyright">
          &copy; Ary Wibowo. Design:
          <a href="http://html5up.net">HTML5 UP</a>.
        </span>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  head: {
    title: 'Ary Wibowo',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'Ary Wibowo'
      }
    ],
  }
};
</script>

<style lang="scss" scoped>
@import '~/assets/sass/main.scss';

body {
  color: #fff;
}
</style>

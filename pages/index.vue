<template>
  <div id="wrapper">
    <div id="bg"></div>
    <div id="overlay"></div>
    <div id="main">
      <header id="header">
        <h1>Ary Wibowo</h1>
        <p>CEO and Founder of <a href="https://curh.at" target="_blank">curh.at</a></p>
        <nav>
          <ul>
            <li>
              <a
                href="https://www.linkedin.com/in/nucreativa/"
                class="icon brands fa-linkedin"
                target="_blank"
              >
                <span class="label">Linkedin</span>
              </a>
            </li>
            <li>
              <a href="https://github.com/nucreativa" class="icon brands fa-github" target="_blank">
                <span class="label">Github</span>
              </a>
            </li>
            <li>
              <a
                href="https://stackoverflow.com/users/2097989/ary-wibowo?tab=profile"
                class="icon brands fa-stack-overflow"
                target="_blank"
              >
                <span class="label">Stack Overflow</span>
              </a>
            </li>
            <li>
              <a
                href="mailto:ary.wibowo@nucreativa.com"
                class="icon solid fa-envelope"
                target="_blank"
              >
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
    title: "Ary Wibowo",
    meta: [
      { charset: "utf-8" },
      { name: "viewport", content: "width=device-width, initial-scale=1" },
      {
        hid: "description",
        name: "description",
        content: "Hi, my name is Ary Wibowo, CEO and Founder of curh.at. And this is my personal website.",
      },
    ],
    script: [
      {
        type: "application/ld+json",
        json: {
          "@context": "http://schema.org",
          "@type": "Person",
          name: "Ary Wibowo",
          gender: "Male",
          nationality: "Indonesia",
          alumniOf: {
            "@type": "OrganizationRole",
            alumniOf: {
              "@type": "CollegeOrUniversity",
              name: "Universitas Gunadarma",
              sameAs: "http://www.gunadarma.ac.id/",
            },
          },
          worksFor: ["Brink's Indonesia"],
          affiliation: [
            "curh.at",
            "Brink's Indonesia",
            "G4S Indonesia",
            "ANTV",
            "Bizzy Indonesia",
            "Icar Asia Limited",
          ],
          sameAs: [
            "https://github.com/nucreativa",
            "https://stackoverflow.com/users/2097989/ary-wibowo?tab=profile",
            "https://www.linkedin.com/in/nucreativa/",
            "https://twitter.com/nucreativa",
          ],
        },
      },
    ],
  },
};
</script>

<style lang="scss" scoped>
@import "~/assets/sass/main.scss";

body,
h1,
p,
a,
span {
  font-family: "Arial" !important;
}
</style>

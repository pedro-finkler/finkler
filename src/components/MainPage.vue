<template>
  <div class="hello">
    <h1>Nice to meet you. I'm Pedro Finkler.</h1>
    <p>
      I'll keep this page updated with my latest projects and experiences.
    </p>
    <h3>Projects</h3>
    <ul>
      <li>
        <a
          href="https://pedro-finkler.github.io/easy-border-radius/"
          target="_blank"
          rel="noopener"
          >Easy Border Radius</a
        >
      </li>
    </ul>
    <h3>Projects I've worked on</h3>
    <ul>
      <li>
        <a
          href="https://leclerc.ca/"
          target="_blank"
          rel="noopener"
          >Leclerc Biscuits</a
        >
      </li>
      <li>
        <a
          href="https://carnaval.qc.ca/"
          target="_blank"
          rel="noopener"
          >Canaval Quebec</a
        >
      </li>
      <li>
        <a
          href="https://certn.co/"
          target="_blank"
          rel="noopener"
          >Certn - Background Checks</a
        >
      </li>
      <li>
        <a
          href="https://www.kaleido.ca/en/"
          target="_blank"
          rel="noopener"
          >Kaleido</a
        >
      </li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li>
        <a
          href="https://github.com/pedro-finkler"
          target="_blank"
          rel="noopener"
          >GitHub</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 10px 10px;
}
a {
  color: #427fb9;
}
</style>

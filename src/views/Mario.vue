<template>
  <div class="hello">
    <p>Practice dd</p>
    <div v-html="htmlContent"></div>
  </div>

</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      htmlContent: "",
    };
  },
  mounted: function () {
    this.loadHtml();
  },
  methods: {
    loadHtml() {
      fetch("./html/processing.html").then((res) => {
        res.text().then((html) => {
          this.htmlContent = html;
          console.log(html)
        });
      });
    },
  },
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
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
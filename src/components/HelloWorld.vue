<template>
  <div>
    <br>
    <br>
    <h1>CenTeam Fisrt Project</h1>
    <br>
    <v-avatar size="300">
      <img
        style="width:200px, height:200px"
        src="https://t1.daumcdn.net/cfile/tistory/2467CC3C5806F2380B"
        alt="handsome"
      >
    </v-avatar>
    <br>
    <v-avatar size="300">
      <img
        style="width:200px, height:200px"
        src="http://t1.daumcdn.net/liveboard/newsade/6e985d24fe8c4986a63463fd5bca21f6.JPG"
        alt="handsome"
      >
    </v-avatar>
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
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

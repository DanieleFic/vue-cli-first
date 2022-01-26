<template>
  <div class="hero">
    <h1>La mia prima app con Vue CLI!</h1>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempore nam animi voluptatum officiis accusamus architecto! Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio minus ea animi perspiciatis aliquam repellendus.</p>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >
.hero {
  width: 700px;
  margin: 0 auto;
  background-color:#00e064;
}

h1{
  color: RGB(0, 20, 52);
  text-align: center;
}

p{
  color: #2c3d34;
}

</style>

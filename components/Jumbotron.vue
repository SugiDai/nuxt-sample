<template>
<div class="bg">
  <div class="jumbotron jumbotron-fluid text-center">
    <div class="container mx-auto">
      <div class="box">
        <h1 class="display-4">Hot Spring</h1>
      </div>
      <div style="height:100px">
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "jumbotron"
};
</script>

<style scoped>
.jumbotron {
  background: url(/onsen_0001.jpg) center no-repeat;
  background-size: cover;
  position: relative;
}

.box {  
  position: absolute;
  margin:15px;
  z-index: 50;
}

.bg {
  background-size: cover;
  position: relative;
}

.bg::before {
  content: " ";
  background-color: rgba(0, 0, 100, 0.3);
  position: absolute;
  z-index: 10;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

h1,
h2 {
  font-weight: 500;
  color: aliceblue;
}

p {
  color: aliceblue;
}

</style>

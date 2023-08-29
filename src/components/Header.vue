<template>
  <div class="hello">
  <h1>My Contact</h1>
  </div>
  <div id="contact">
   <p>GitHub: <a href="https://github.com/pornthida030?tab=repositories">Pornthida Suksankawanchi</a></p>
   <p>Email: pornthida.suks@ku.th</p>
   <p>Tel: 0804497527</p>
  </div>
</template>

<script>
export default {
  name: 'Header_1'
}
</script>


<style scoped>
.hello{
  background-color: chocolate;
  padding: 30px 20px 30px 20px;
  text-align: center;
  margin: 0px;
  color: white;
  
}
#contact {
  margin: 40px 0 0;
  color: #000000;	
}
a:link{
  color: #000000;
  text-decoration:none;
}
a:hover{
  color:#A52A2A;
  text-decoration:none
}
</style>

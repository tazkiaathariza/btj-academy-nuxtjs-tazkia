<template>
  <div class="container">
 
  <div class="row">
    <div class="col d-flex justify-content-center my-5">
      <div class="box p-5 my-5">
          <FormLogin />
        </div>
    </div>
  </div>
  </div>
</template>

<script>
definePageMeta({
  layout:'auth'
})
</script>

<style scoped>
.box {
  width: 50%;
  color: #2A2A2A;
  align-items: center;
  background-color: white;
  border-radius: 15px;
  box-shadow: 0 0 4px rgba(255, 255, 255, 0.3);
}

@media (max-width: 768px) {
  .box {
    width: 85%;
  }
}

@media screen and (min-width : 768px) and (max-width : 1024px) {
  .box {
    width: 70%;
  }
}
</style>

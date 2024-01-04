<template>
<div class="container admin">
  <h3 class="my-4">Introduction</h3>
  <div class="my-4 mx-2">
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">Name</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Put your name">
    </div>
    <div class="mb-4">
      <label for="formFile" class="form-label">Picture</label>
      <input class="form-control" type="file" id="formFile">
    </div>
    <div class="mb-3">
      <label for="exampleFormControlTextarea1" class="form-label">Introduction Paragraph</label>
      <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="Explain, please"></textarea>
    </div>
    <button class="btn btn-danger">Submit</button>
  </div>
</div>
  
</template>

<script>
definePageMeta({
  layout:'default'
})
</script>

<style>
.form-label,
.admin {
  color: white;
}
</style>
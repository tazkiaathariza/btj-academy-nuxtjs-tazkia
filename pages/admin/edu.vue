<template>
<div class="container admin">
  <h3 class="my-4">Education</h3>
  <div class="my-4 mx-2">
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">University/School</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Input name of your univ">
    </div>
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">Year</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Input year">
    </div>
    <div class="mb-4">
      <label for="exampleFormControlInput1" class="form-label">Major and GPA</label>
      <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Input major and GPA">
    </div>
    <div class="mb-3">
      <label for="exampleFormControlTextarea1" class="form-label">Add Explanation</label>
      <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Explain, please" rows="3"></textarea>
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
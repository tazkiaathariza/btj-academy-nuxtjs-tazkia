<template>
        <h4>Welcome to Admin Page!</h4>
       <form id ="formLogin" class="my-3" novalidate>
        <label for="nama">Username</label>
        <br/>
        <div class="userInput">
          <input type="text" id="nama" name="nama" placeholder="Insert your username" required>
          <br/>
          <p id="pesanNama" class="pesanError"></p>
        </div>
          <br/>
          <label for="password">Password</label>
          <br/>
          <div class="userInput">
            <input type="password" id="password" name="password" placeholder="Insert your password" required>
            <br/>
            <p id="pesanPassword" class="pesanError"></p>
            <p id="reminderCapslock" class="pesanError" style="margin-top: 2px;"></p>
          </div>
          <br/>
             <button class="btn btn-primary loginButton" @click="toIntro">Log In</button>
        </form>
</template>

<script>
export default {
    methods: {
        toIntro(){
            alert("Anda berhasil login")
            navigateTo('/admin/intro')
        }
    }
}
</script>

<style>
input {
  width: 100%
}

.loginButton {
  width: 100%;
}
</style>
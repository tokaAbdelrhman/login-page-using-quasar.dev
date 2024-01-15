<template>
  <q-layout view="lHh Lpr lFf" class="app">
    <div class="row">
      <div class="col-12 col-md-4 col-lg-4 q-pa-xl text-center">
        <div class=" text-center">
          <q-img class="logo" src="src/assets/login.jpg" alt=""></q-img>
        </div>
        <div class="text-h4 text-bold q-mt-lg">view list</div>
        <div class="text-gray-7">Please Login Your Account Below</div>
        <q-input
        outlined
        label="Enter Email "

        >
        <template v-slot:append>
          <q-icon name="email">
          </q-icon>
        </template>
        </q-input>
        <q-input
        class="q-mt-sm"
        outlined
        label="Enter Password "

        >
        <template v-slot:prepend>
          <q-icon name="lock">
          </q-icon>
        </template>
        <template v-slot:append>
          <q-icon name="visibility_off">
          </q-icon>
        </template>


        </q-input>
        <div  class="q-mt-sm column">
        <q-btn
        color="indigo"

        >
        login

        </q-btn>
      </div>
      </div>
      <div class="col-12 col-md-8 col-lg-8 q-pa-xl ">
        <q-img src="src/assets/dow.jpg" class="login-page"></q-img>
      </div>

    </div>

 </q-layout>
</template>

<script>

</script>
<style>

.logo{
  width:200px;

  height:200px;
  border-radius: 50%;
}
.login-page{
  width:400px;

  height:400px;
}
</style>

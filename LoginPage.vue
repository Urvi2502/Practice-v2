<template>
  <q-card class="my-card" flat bordered>
    <h3 class="row justify-center"></h3>
    <q-card-section horizontal style="display: flex; justify-content: space-between; ">
      
      <q-card-section class="col justify-left">
        <form action="post" style="padding: 200px">
          <p>
            <input v-model="message" type="text" style="width: 400px; height: 50px">
          </p>
          <p>
            <input type="password" v-model="password" style="width: 400px; height: 50px">
          </p>
            <button type="submit">Add item</button>
        </form>
      </q-card-section>

      <q-img 
        class="row justify-right"
        style="width: 50%; height: auto; max-height: 50vh;align-items: right;" 
        src="/src/assets/login.jpg"
      />
    </q-card-section>
  </q-card>
</template>

  
  <script>
    import { defineComponent } from 'vue';
    export default defineComponent({
      name: "LoginPage",

    });
  </script>
  
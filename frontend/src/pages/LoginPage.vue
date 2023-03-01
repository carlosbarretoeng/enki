<template>
  <div class="fullscreen bg-primary row wrap justify-center items-center">
    <q-card class="q-pa-md">
      <q-card-section>
        <!-- <q-form @submit.prevent="login">
          <q-input outlined v-model="email" label="Email" type="email" />
          <q-input outlined v-model="password" label="Password" type="password" />
          <q-btn type="submit" label="Login" color="primary" />
        </q-form> -->
      </q-card-section>
    </q-card>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const email = ref('');
const password = ref('');

function login() {
  // Add your login logic here, using Axios or other HTTP client library
}
</script>

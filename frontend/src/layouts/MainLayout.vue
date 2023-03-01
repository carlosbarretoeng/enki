<template>
  <q-layout view="hHh lpR fFf">

    <q-header reveal elevated class="bg-primary text-white q-pa-sm">
      <q-toolbar>
        <q-toolbar-title>
          AGOSTINI
        </q-toolbar-title>

        <q-separator vertical class="q-mr-md" />

        <div class="q-mr-md">
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
        </div>

        <q-separator vertical class="q-mr-md" />

        <div>
          <q-list>
            <q-item class="q-my-sm" clickable v-ripple>
              <q-item-section>
                <q-item-label>contact.name</q-item-label>
                <q-item-label caption lines="1">contact.email</q-item-label>
              </q-item-section>

              <q-item-section side>
                <q-avatar color="primary" text-color="white">
                  KJ
                </q-avatar>
              </q-item-section>
            </q-item>
          </q-list>
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script setup lang="ts">
</script>

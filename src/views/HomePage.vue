<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Homenaje</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content class="ion-padding">
      <div id="container">
        <h2>Operaciones matemáticas</h2>

        <p>Suma: {{ numero1 }} + {{ numero2 }} = {{ numero1 + numero2 }}</p>

        <p>Resta: {{ numero1 }} - {{ numero2 }} = {{ numero1 - numero2 }}</p>

        <p>Multiplicación: {{ numero1 }} * {{ numero2 }} = {{ numero1 * numero2 }}</p>

        <p>División: {{ numero1 }} / {{ numero2 }} = {{ numero1 / numero2 }}</p>
      </div>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar
} from '@ionic/vue';

// Variables constantes no reactivas
const numero1 = 6;
const numero2 = 5;
</script>
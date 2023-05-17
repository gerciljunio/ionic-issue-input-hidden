<template>
  <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>TItle</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <ion-searchbar></ion-searchbar>
            <ion-card>
                <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/card-media.png" />
                <ion-card-header>
                    <ion-card-title>Card Title</ion-card-title>
                    <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
                </ion-card-header>

                <ion-card-content>
                    Here's a small text description for the card content. Nothing more, nothing less.
                </ion-card-content>
            </ion-card>
            <!-- <ion-searchbar></ion-searchbar> -->
            <ion-card>
                <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/card-media.png" />
                <ion-card-header>
                    <ion-card-title>Card Title</ion-card-title>
                    <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
                </ion-card-header>

                <ion-card-content>
                    Here's a small text description for the card content. Nothing more, nothing less.
                    <ion-textarea label="Solid textarea" labelPlacement="floating" fill="solid"
                        placeholder="Enter text"></ion-textarea>

                    <br>
                    <ion-input label="Default inputssss" inputmode="text"></ion-input>

                    <ion-button color="tertiary">Tertiary</ion-button>
                    <ion-button color="success">Success</ion-button>
                    <ion-button color="warning">Warning</ion-button>

                </ion-card-content>
            </ion-card>
        </ion-content>
    </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton, IonInput, IonTextarea } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>

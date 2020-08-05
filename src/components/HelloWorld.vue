<template>
  <div>
    <v-container>
      <v-row>
        <v-col>
          <v-card>
            <v-card-title>
              Hello World
            </v-card-title>
            <v-card-text>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae doloribus delectus ipsam omnis accusamus sit molestiae atque laboriosam quidem, id eum cupiditate totam asperiores, ipsum dignissimos dolorem porro? Labore, repellat?
            </v-card-text>
          </v-card>
        </v-col>
      </v-row>
    </v-container>

  </div>
</template>

<script>
  import { VContainer, VRow, VCol, VCard, VCardText, VCardTitle } from 'vuetify/lib'

  export default {
    name: 'HelloWorld',
    components: {
      VContainer,
      VRow,
      VCol,
      VCard,
      VCardText,
      VCardTitle
    }
  }
</script>

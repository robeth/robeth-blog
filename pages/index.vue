<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <v-card>
        <v-card-title class="headline">Hi, I am Robeth!</v-card-title>
        <v-card-text>
          <p>
            A happy and proud codenaut. Currently I am working as a full-stack
            engineer. Loving my family and daily life so far. And I hope you are
            too!
          </p>
        </v-card-text>
      </v-card>
    </v-flex>
    <div class="headline my-4">Blog</div>
    <v-flex xs12 sm12 md6>
      <v-card>
        <v-card-title>Vue Wrapper Component</v-card-title>
        <v-card-text
          >Forward props and slots of base component to improve reusability
        </v-card-text>
        <v-card-actions>
          <div>
            <v-icon>mdi-calendar</v-icon>
            <span>2020 April 04</span>
          </div>
          <v-spacer />
          <v-btn>Read</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  components: {}
};
</script>

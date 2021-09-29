<template>
  <v-app>
    <v-main>
      <v-container>
        <v-row align="center" justify="center">
          <v-col cols="12" sm="10">
            <v-card class="elevation-6 mt-10">
              <v-window v-model="step">
                <signin @increaseStep="step++"></signin>
                <signup @decreaseStep="step--"></signup>
              </v-window>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Signin from './components/Signin.vue'
import Signup from './components/Signup.vue'

export default {
  components: {
    Signin,
    Signup
  },
  data() {
    return {
      step: 1
    }
  }
}
</script>

<style>
.v-application .rounded-bl-xl {
  border-bottom-left-radius: 300px !important;
}

.v-application .rounded-br-xr {
  border-bottom-right-radius: 300px !important;
}
</style>

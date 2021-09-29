<template>
  <v-window-item :value="2">
    <v-row>
      <v-col cols="12" sm="6" class="blue rounded-br-xr">
        <div style="text-align: center; padding: 180px 0;">
          <v-card-text class="white--text">
            <h3 class="text-center">Already signed up?</h3>
            <h6 class="text-center">
              Sign in to you account so you can continue building and
              <br />editing your onboarding flows
            </h6>
          </v-card-text>
          <div class="text-center">
            <v-btn tile outlined dark @click="$emit('decreaseStep')">Sign in</v-btn>
          </div>
        </div>
      </v-col>
      <v-col cols="12" sm="6">
        <v-card-text class="mt-12">
          <h4 class="text-center">Sign up for an account</h4>
          <h6 class="text-center grey--text">
            Let's get you all set so you can start creating your
            <br />
            first onboarding experience
          </h6>
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8">
              <v-row>
                <v-col cols="12" sm="6">
                  <v-text-field
                    label="First name"
                    outlined
                    dense
                    color="blue"
                    class="mt-4"
                  ></v-text-field>
                </v-col>
                <v-col cols="12" sm="6">
                  <v-text-field
                    label="Last name"
                    outlined
                    dense
                    color="blue"
                    class="mt-4"
                  ></v-text-field>
                </v-col>
              </v-row>
              <v-text-field
                label="E-mail"
                outlined
                dense
                color="blue"
              ></v-text-field>
              <v-text-field
                label="Password"
                outlined
                dense
                color="blue"
                type="password"
              ></v-text-field>
              <v-row>
                <v-col cols="12" sm="7">
                  <v-checkbox
                    label="I accept the terms"
                    class="mt-n1"
                    color="blue"
                  ></v-checkbox>
                </v-col>
                <v-col cols="12" sm="5">
                  <span class="caption blue--text ml-n4"
                    >Terms & conditions</span
                  >
                </v-col>
              </v-row>
              <v-btn color="blue" dark block tile>Sign up</v-btn>
              <h5 class="text-center grey--text mt-4 mb-3">Or sign up using</h5>
              <div
                class="d-flex justify-space-between align-center mx-10 mb-11"
              >
                <v-btn depressed outlined color="grey">
                  <v-icon color="red">fab fa-google</v-icon>
                </v-btn>
                <v-btn depressed outlined color="grey">
                  <v-icon color="blue">fab fa-facebook-f</v-icon>
                </v-btn>
                <v-btn depressed outlined color="grey">
                  <v-icon color="light-blue lighten-3">fab fa-twitter</v-icon>
                </v-btn>
              </div>
            </v-col>
          </v-row>
        </v-card-text>
      </v-col>
    </v-row>
  </v-window-item>
</template>

<script>
export default {}
</script>

<style></style>

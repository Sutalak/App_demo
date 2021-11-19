<template>
  <div class="bg1" justify="center" align="center">
    <p class="f1">
      Sign up your bank account
    </p>
    <v-form>
      <v-container fluid>
        <v-row>
          <v-col
            cols="12"
            sm="6"
            md="3"
          >
            <v-text-field
              label="Your Name"
              outlined
              light
              radius
            />
          </v-col>
          <v-col
            class="row1"
            cols="12"
            sm="6"
            md="3"
          >
            <v-text-field
              label="Bank Account"
              outlined
              light
              radius
            />
          </v-col>
          <v-col
            class="row1"
            cols="12"
            sm="6"
            md="3"
          >
            <v-text-field
              label="Mobie phone number"
              outlined
              light
              radius
            />
          </v-col>
          <v-col
            class="row1"
            cols="12"
            sm="6"
            md="3"
          >
            <v-text-field
              label="Email"
              outlined
              light
              radius
            />
          </v-col>
          <v-col
            class="row1"
            cols="12"
            sm="6"
          >
            <v-text-field
              label="Password"
              outlined
              light
              radius
              append-icon="mdi-eye"
            />
          </v-col>
          <v-col
            class="row1"
            align="left"
            cols="12"
            sm="6"
          >
            <p class="f1">
              User 6 characters with amix of numbers and letters
            </p>
          </v-col>
          <v-col class="row1" cols="12" sm="6">
            <v-checkbox
              label="By signing up, you agree to Bank's Term of Use & Privacy Policy."
              value
              indeterminate
              light
            />
          </v-col>
          <v-col
            class="row2"
            cols="12"
            sm="6"
          >
            <v-btn class="btn1">
              <span class="txt1">SIGN UP</span>
            </v-btn>
            or
            <v-btn class="btn2">
              <span class="txt1">SIGN UP</span>
            </v-btn>
          </v-col>
          <v-col
            class="row2"
            cols="12"
            sm="6"
          >
            <p>Already signed up? Login</p>
          </v-col>
        </v-row>
      </v-container>
    </v-form>
  </div>
</template>
<style>
  .bg1{
    background-color: white;
    border-radius: 25px;
    padding: 20px;
    color: black;
  }
  .row1{
    margin-top: -35px;
  }
  .row2{
    margin-top: -20px;
  }
  .f1{
    color: #0989ff;
  }
  .btn1{
    background: linear-gradient(to bottom,#ffeb3b,#ffc107);
    margin: 10px;
  }
  .btn2{
    background: linear-gradient(to bottom,#ffffff,#ececec);
    margin: 10px;
  }
  .txt1{
    color: black;
  }
</style>

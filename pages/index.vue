<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="pa-7 white rounded-circle d-inline-block">
        <!-- <v-icon large> mdi-arrow-up-bold-box-outline </v-icon> -->
        <i class="fas fa-university" style="color: #0989ff; font-size: 40px;" />
      </div>
      <div style="margin-top: 5%;">
        <h1>KNN BANK</h1>
        <h3>MOBILE APP</h3>
      </div>
      <v-form style="margin-top: 8%;">
        <v-container>
          <v-col cols="12" sm="8" md="6">
            <v-menu transition="scroll-x-transition">
              <template #activator="{ on, attrs }">
                <v-text-field
                  label="PLEATE ENTER YOUR PASSWORD"
                  placeholder="PASSWORD"
                  filled
                  rouded
                  dense
                  v-bind="attrs"
                  v-on="on"
                />
              </template>
              <div class="box">
                <v-row>
                  <v-col class="d-flex justify-center mb-6">
                    <v-btn class="mx-2" fab dark large color="primary">
                      1
                    </v-btn>
                    <v-btn class="mx-2" fab dark large color="primary">
                      2
                    </v-btn>
                    <v-btn class="mx-2" fab dark large color="primary">
                      3
                    </v-btn>
                  </v-col>
                  <v-col class="d-flex justify-center mb-6" style="margin-top:-35px;">
                    <v-btn class="mx-2" fab dark large color="primary">
                      4
                    </v-btn>
                    <v-btn class="mx-2" fab dark large color="primary">
                      5
                    </v-btn>
                    <v-btn class="mx-2" fab dark large color="primary">
                      6
                    </v-btn>
                  </v-col>
                  <v-col class="d-flex justify-center mb-6" style="margin-top:-35px;">
                    <v-btn class="mx-2" fab dark large color="primary">
                      7
                    </v-btn>
                    <v-btn class="mx-2" fab dark large color="primary">
                      8
                    </v-btn>
                    <v-btn class="mx-2" fab dark large color="primary">
                      9
                    </v-btn>
                  </v-col>
                  <v-col class="d-flex justify-center mb-6" style="margin-top: -35px">
                    <v-btn class="mx-2" fab dark large color="primary">
                      0
                    </v-btn>
                  </v-col>
                </v-row>
              </div>
            </v-menu>
            <v-btn class="btn1">
              <span class="txt1">LOG IN</span>
            </v-btn>
            <div style="margin-top: 10%;">
              <p>Forgot password?</p>
              <p>New to Bank App?Sign Up</p>
            </div>
          </v-col>
        </v-container>
      </v-form>
    </v-col>
  </v-row>
</template>

<style>
  .pa-7{
    margin-top: 100px;
  }
  .h3{
    margin-top: 50px;
  }
  .txt1{
    color: brown;
  }
  .btn1{
    background: linear-gradient(to bottom,#ffeb3b,#ffc107);
    margin-bottom: 50px;
  }
  .box{
    background-color: white;
    padding: 15px;
    border-radius: 25px;
    font-size: 18px;
  }
</style>

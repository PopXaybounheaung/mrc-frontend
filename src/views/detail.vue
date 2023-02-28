<template>
    
    <div>

        <v-app-bar color="#fff" density="prominent" class="p-1">
          <template v-slot:prepend>
            <v-btn icon>
                <span class="bi bi-arrow-left" style="font-size: 20px;"></span>
            </v-btn>
          </template>
          <div>
                <v-text style="font-size: 35px;"> Khountathong</v-text>
                <br>
                <p style="font-size: 20px; text-align: center;"> Vientaine, Laos</p>
            </div>
          <template v-slot:append>
            <v-btn class="text-none" icon>
              <v-badge content="2" color="error">
                <span id="boot-icon" class="bi bi-info-circle" style="font-size: 20px;"></span>
              </v-badge>
            </v-btn>
          </template>
        </v-app-bar>

        <v-card
    class="mx-auto mt-5" 
    width="500"
    > 
    <div style="background-color: green;
   border-radius: 14px;
    text-align: center;
    margin: 0px;
    display: inline-block;
    padding: 17px;
    margin: 12px;" >
    <p>Moisture</p>
    <img src="" alt="">
    <p>57.3 %</p>

  </div>
        </v-card>

        <v-card
    class="mx-auto mt-5" 
    width="500"
    > 
    <div style="background-color:#204F97;
    border-radius: 14px;
    text-align: center;
    margin: 0px;
    display: inline-block;
    padding: 17px;
    margin: 12px;" >
    <p>Moisture</p>
    <img src="" alt="">
    <p>57.3 %</p>

  </div>
        </v-card>


        <v-card
    class="mx-auto mt-5" 
    width="500"
    > 
  <div style="
    border-radius: 14px;
    text-align: center;
    margin: 0px;
    display: inline-block;
    padding: 10px;
    margin: 12px;" >
    <p>PH</p>
    <img src="" alt="">
    <p>10</p>

  </div>
        </v-card>

        <v-card
    class="mx-auto mt-5" 
    width="500"
    > 
  <div style="
    border-radius: 14px;
    text-align: center;
    margin: 0px;
    display: inline-block;
    padding: 10px;
    margin: 12px;" >
    <p>Temperature</p>
    <img src="" alt="">
    <p></p>

  </div>
        </v-card>

 
  </div>

  </template>
  
  <script lang="ts">
  export default {
      data: () => ({
        tab: null,
      }),
    }
  </script>
  
<style lang="scss" scoped>

</style>
  
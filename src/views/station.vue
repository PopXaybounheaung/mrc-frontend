<template>
  <div>
    <v-card max-width="500" class="mx-auto">
      <v-layout>
        <v-app-bar color="#fff" density="prominent" class="p-1">
          <template v-slot:prepend>
            <v-btn icon>
              <v-icon>mdi-magnify</v-icon>
            </v-btn>
          </template>

          <template v-slot:append>
            <v-btn class="text-none" icon>
              <v-badge content="2" color="error">
                <v-icon>mdi-bell-outline</v-icon>
              </v-badge>
            </v-btn>
          </template>
        </v-app-bar>
        <v-main>
          <v-container fluid>
           <v-card>
          <v-tabs v-model="tab" bg-color="#FFF">
            <v-tab value="one">Online</v-tab>
            <v-tab value="two">Offline</v-tab>
          </v-tabs>

          <v-card-text>
            <v-window v-model="tab">
              <v-window-item value="one"> 
                <v-card
            border
            class="mb-2"
            density="compact"
            min-height="200px"
            max-height="500px"
          >
           <v-row>
            
           </v-row>
          </v-card>
                 </v-window-item>

              <v-window-item value="two"> Two </v-window-item>
            </v-window>
          </v-card-text>
        </v-card>
          </v-container>
        </v-main>
      </v-layout>
    </v-card>
  </div>
</template>

<script>
export default {
    data: () => ({
      tab: null,
    }),
  }
</script>

<style lang="scss" scoped></style>

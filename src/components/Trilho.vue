<template>
   <v-app>
        <form action="" id="trilho">
            <fieldset>

                <legend>Balastro:</legend>

                <div class="input_largura">
                    <label for="largura">Largura:</label>
                    <input type="number" name="largura" id="largura" required>
                    <label for=""> m</label>
                </div>

                <div class="input_declive">
                    <label for="declive">Declive(%):</label>
                    <input type="number" name="declive" id="declive" required>
                    <label for=""> m</label>
                </div>

                <div class="input_altura">
                    <label for="autura">Autura:</label>
                    <input type="number" name="autura" id="autura" required>
                    <label for=""> m</label>
                </div>

                <div class="check_elevacao">
                    <input type="checkbox" name="elevacao" id="elevacao" required>
                    <label for="elevacao">Super Elevação</label>
                </div>

                <legend>Rastrear:</legend>

                <div class="input_medidor">
                    <label for="rastrear">Medidor ½</label>
                    <input type="number" name="medidor" id="medidor" required>
                    <label for=""> m</label>
                </div>

            </fieldset>
        </form>
    </v-app>
</template>

<script>
  export default {
    name: 'Trilho',
  }
</script>  





















<!-- //   <v-app>
//     <v-app-bar
//       app
//       color="primary"
//       dark
//     >
//       <div class="d-flex align-center">
//         <v-img
//           alt="Vuetify Logo"
//           class="shrink mr-2"
//           contain
//           src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
//           transition="scale-transition"
//           width="40"
//         />

//         <v-img
//           alt="Vuetify Name"
//           class="shrink mt-1 hidden-sm-and-down"
//           contain
//           min-width="100"
//           src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
//           width="100"
//         />
//       </div>

//       <v-spacer></v-spacer>

//       <v-btn
//         href="https://github.com/vuetifyjs/vuetify/releases/latest"
//         target="_blank"
//         text
//       >
//         <span class="mr-2">Latest Release</span>
//         <v-icon>mdi-open-in-new</v-icon>
//       </v-btn>
//     </v-app-bar>

//     <v-main>
//       <HelloWorld/>
//     </v-main>
//   </v-app> -->
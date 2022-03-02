<template>
    <v-app>
        <form action="" id="movimento">
            <fieldset>

                <legend>Vista de Movimento:</legend>

                <div class="selection_movimento">
                    <input type="radio" name="movimento" value="esquerda" id="esquerda">Esquerda
                    <input type="radio" name="movimento" value="direita" id="direita" checked>Direita
                    <input type="radio" name="movimento" value="ambos" id="ambos">Ambos
                </div>

                <legend>Ver:</legend>

                <div class="selection_ver">
                    <input type="radio" name="ver" value="cortar" id="cortar" checked>Cortar
                    <input type="radio" name="ver" value="preencher" id="preencher">Preencher
                </div>

                <legend>Índice V:H</legend>
                <div class="selection_indice">
                    <select name="indice">
                        <option value="1">1:1</option>
                        <option value="2">2:2</option>
                        <option value="3">3:3</option>
                    </select>
                </div>

                <div class="check_zoom">
                    <input type="checkbox" name="zoom" id="zoom" required>
                    <label for="zoom">Zoom Ajuste</label>
                </div>

            </fieldset>
        </form>
    </v-app>    
</template>

<script>
  export default {
    name: 'Modelo',
  }
</script>  
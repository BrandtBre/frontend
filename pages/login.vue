<template>
  <v-container>
    <v-container style="margin-top: 220px">
      <v-row>
        <v-col>
          <h1>rocketseat</h1>
        </v-col>
      </v-row>
    </v-container>
    <v-container style="margin-top: 70px">
      <v-row>
        <v-col>
          <h1 style="font-size: 55px">Faça seu login</h1>
          <h1 style="font-size: 55px">na plataforma</h1>
        </v-col>
        <v-col>
          <form action="">
            <v-text-field
              v-model="Email"
              label="Email"
              prepend-inner-icon="mdi-email"
            >
            </v-text-field>
            <v-text-field
              v-model="Senha"
              label="Senha"
              prepend-inner-icon="mdi-lock"
            ></v-text-field>
            <v-btn style="background-color:blueviolet; text-align: center;">ENTRAR</v-btn>
            <p style="text-align: center;">Não tem uma conta? Registre-se</p>
          </form>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default {

}
</script>

<style>

</style>
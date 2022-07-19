<template>
  <v-container>
    <v-container style="margin-top: 200px">
      <v-row>
        <v-col>
          <h1><v-icon style="color:blueviolet">mdi-rocket-launch</v-icon>rocketseat</h1>
        </v-col>
      </v-row>
    </v-container>
    <v-container style="margin-top: 60px">
      <v-row>
        <v-col>
          <h1 style="font-size: 55px">Faça seu login</h1>
          <h1 style="font-size: 55px">na plataforma</h1>
        </v-col>
        <v-col>
          <v-container style="padding:20%; background-color:#202024; border-radius:5px; margin-top: -200px;">
            <form action="">
              <v-text-field
                outlined
                v-model="Email"
                label="Email"
                prepend-inner-icon="mdi-email"
                color="#8d30e2"
                background-color="#121214"               
              >
              </v-text-field>           
              <v-text-field
                outlined
                v-model="Senha"
                label="Senha"
                prepend-inner-icon="mdi-lock"
                color="#8d30e2"
                background-color="#121214"

                
              ></v-text-field>
              <v-col style="margin-top: -38px">
                <a href="forgotPassword" style="font-weight:bold; color:blueviolet; font-size: 15px;">
                  Esqueci minha senha
                </a>
              </v-col>        
              <v-btn style="background-color:#8d30e2; width: 100% ; margin-top: 15px; padding: 7%">ENTRAR</v-btn>
              <p style="text-align: center; margin-top: 20px;">Não tem uma conta? <a style="font-weight:bold; color:blueviolet; ">Registre-se</a></p>
              <v-row>
                <v-col>
                  <hr>
                </v-col>
                <v-col>
                  <hr>
                </v-col>
              </v-row>
              <v-row>
                <v-col style="text-align: center; margin-top: 5px">
                  <p>Ou entre com</p>
                </v-col>
                <v-col>                 
                  <v-btn style="background-color:#8d30e2; width: 100%;"> <v-icon>mdi-github</v-icon>GITHUB</v-btn>                 
                </v-col>
              </v-row>
            </form>
          </v-container>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default {
  name: 'loginPage',
  data () {
    return {

    }
  },
  methods: {

  }

}
</script>

<style>
a{
  color: blueviolet;
  text-decoration: none;
}
</style>
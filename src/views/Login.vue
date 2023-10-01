<template>
  <div class="login">
    <div class="d-flex align-center justify-center" style="height: 80vh">
        <v-sheet width="400" class="mx-auto">
            <v-form fast-fail @submit.prevent="login">
                <v-text-field variant="outlined" v-model="email" label="E-mail"></v-text-field>

                <v-text-field variant="outlined" v-model="password" label="Password"></v-text-field>

                <v-btn type="submit" color="primary" block class="mt-2">Войти</v-btn>

            </v-form>
        </v-sheet>
    </div>
  </div>
</template>

<script>

export default {
  name: "Login",
  components: {
    
  },
  data() {
    return {
      email: '',
      password: ''  
    };
  },
  computed: {
    
  },
  methods: {
    login() {
        // Your login logic here
    },
  },
  created() {
    
  }
};
</script>

<style scoped lang="scss">

</style>

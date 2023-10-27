<template>
  <div class="d-flex justify-center align-center h-screen">
  <v-sheet width="300">
    <v-form fast-fail @submit.prevent="submit">
      <v-text-field
        v-model="form.email"
        label="Email"
        :rules="nameRules"
        type="email"
      ></v-text-field>

      <v-text-field
      v-model="form.password"
      label="Password"
      type="password"
    ></v-text-field>

      <v-btn type="submit" block class="mt-2" color="success">Submit</v-btn>
    </v-form>
  </v-sheet>
</div>
</template>

<script>

export default {
  name: 'Login',
  data(){
    return{
      form:{
        email: '',
        password:null
      }
    }
  },
  methods:{
    submit(){
      localStorage.setItem("email",this.form.email)
      localStorage.setItem("password",this.form.password)
      localStorage.setItem("tokenId","secret key")
    }
  }

  
}
</script>

<template>
  <div class="login">
      <b-jumbotron bg-variant="info" text-variant="white"/>
      <b-container>
        <b-row>
          <b-col lg="4" md="3"></b-col>
          <b-col lg="4" md="6">
            <LoginForm/>
          </b-col>
          <b-col lg="4" md="3"></b-col>
        </b-row>
      </b-container>
  </div>
</template>

<script>
import LoginForm from '../components/LoginForm.vue'
export default {
  name: 'login',
  components: {
    LoginForm
  }

}
</script>

<style>

</style>
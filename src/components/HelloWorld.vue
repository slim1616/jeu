<template>
  <div class="container">
      <div class="row">
        <div class="col-sm-6">
          
           <router-link class="nav-link btn btn-primary" to="/listen">Parler</router-link>
        </div>
         <div class="col-sm-6">
          <router-link class="nav-link btn btn-primary" to="/listen">Chercher</router-link>
          
        </div>
      </div>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

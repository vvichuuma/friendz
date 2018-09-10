<template>
  <div class="home">
    

   <nav class="navbar navbar-light" style="background-color: red;">
      
    <h2>Holy Shit!!!</h2>


      <h2 >DG</h2>

   </nav>



    <router-link = "./pageb">
   <button id="shy" v-on:click="ale()">Goes to Page b</button>
 </router-link>



  </div>
</template>

<style>

   #shy{


       position: absolute;
       left:660px;
       top:400px;

   }



</style>

<script>
export default {
  data: function() {
    return {
      

   




    };
  },
  created: function() {},
  methods: {

    ale: function() {

       

    }

    



  },
  computed: {}
};
</script>

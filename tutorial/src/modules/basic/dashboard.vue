<template>
    <div id ="dashboard">
        <Header2></Header2>
        <Sidebar id="sidebar" v-if="!isHidden"></Sidebar>
        <div id="dash">
        <center>
        <div class="container-fluid">
        <br><br>
            <h1>EASAKAY</h1>
            <p><i>Makes your travel Easier!</i></p>
            <img src="https://cdn.citylab.com/media/img/citylab/2018/07/E500_NA_Foothill_Side_Front_view/facebook.jpg?1531425508">
        </div>
        </center>
        </div>
    </div>
    
</template>

<script>
import Sidebar from 'components/frame/Sidebar.vue'
import Header2 from 'components/frame/Header2.vue'
export default {
  name: 'dashboard',
  data() {
      return{
        isHidden: false
      }
  },
  components: {
      Header2,
      Sidebar
  }
}

</script>
<style>
Sidebar{
    display: none;
}
h1{
    font-size: 28px;
    font-family: 'Lucida Calligraphy';
}

</style>
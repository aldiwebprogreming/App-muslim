<template>
  <div class="home">
    <Navbar/>
    <div class="container mt-4 mb-5">
      <div class="row">
        <div class="col-md-6 offset-md-3">
          <Hero/>
          <Menu_card/>

          <!-- tentang kami -->
          <div class="card mt-4">
          <div class="card-body">
            <h6><strong><i class="fas fa-home"></i> Tentang kami</strong></h6>
            <hr>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Labore praesentium, minus fugit, commodi dicta error nobis voluptate non
             voluptas architecto ea, recusandae ad? Quasi saepe eveniet necessitatibus 
             asperiores mollitia repudiandae?.
             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo asperiores facere dolorem accusamus voluptates, ducimus itaque, debitis velit inventore commodi sint veritatis corporis enim minus harum magnam sunt unde sit!</p>
          </div>
         </div>

          <!-- Donasi untuk kami -->
         <div class="card mt-4">
          <div class="card-body">
            <h6><strong><i class="fas fa-box"></i> Donasi Aplikasi</strong></h6>
            <hr>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Labore praesentium, minus fugit, commodi dicta error nobis voluptate non.
        
          </div>
         </div>

         

        </div>
      </div>
      
    </div>

    <Footer/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Hero from '@/components/Hero.vue'
import Menu_card from '@/components/Menu_card.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'Home',
  components: {
    Navbar,
    Hero,
    Menu_card,
    Footer,
  
  }
}
</script>

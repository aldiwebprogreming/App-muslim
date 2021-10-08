<template>
  <div class="masjid">
    <Navbar/>
        <div class="container mt-4 mb-5">
            <div class="row">
                 <div class="col-md-6 offset-md-3">
                     <div class="card">
                        <div class="card-body">
                           <h6><i class="fas fa-mosque"></i> <strong> Cari Lokasi Masjid </strong></h6>
                           <hr>
                            <form action="">
                                <div class="input-group mb-3">
                                    <input type="text" class="form-control" placeholder="Cari lokasi masjid" aria-label="Recipient's username" aria-describedby="basic-addon2">
                                    <div class="input-group-append">
                                        <button type="submit" class="btn btn-secondary"><i class="fas fa-search search"></i></button>
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>


                    <!-- list data masjid -->
                    <div class="card mt-3">
                        <div class="card-body">
                            <div class="row">
                                <div class="col-sm-6">
                                    <img src="../assets/masjid/masjid1.jpg" class="rounded float-left masjid" alt="">
                                </div>
                                <div class="col-sm-6">
                                    <label for=""><strong>Masjid Raya Medan</strong></label>
                                    <label for="">Alamat : Jl. Asrama medan Kota Medan Sumut.</label>
                                    <hr>
                                    <small for=""><strong>Tentang</strong></small>
                                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. A distinctio. <a href="">Read more</a></p>

                                </div>

                            </div>
                        </div>
                    </div>

                    <div class="card mt-3">
                        <div class="card-body">
                            <div class="row">
                                <div class="col-sm-6">
                                    <img src="../assets/masjid/masjid2.jpg" class="rounded float-left masjid" alt="">
                                </div>
                                <div class="col-sm-6">
                                    <label for=""><strong>Masjid Azizi Langkat</strong></label>
                                    <label for="">Alamat : Jl. Kecamatan Tanjung Pura Kab.Langkat.</label>
                                    <hr>
                                    <small for=""><strong>Tentang</strong></small>
                                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. A distinctio. <a href="">Read more</a></p>

                                </div>

                            </div>
                        </div>
                    </div>
                    <!-- end -->

                    <div class="card mt-3 mb-5">
                        <div class="card-body">
                            <div class="row">
                                <div class="col-sm-6">
                                    <img src="../assets/masjid/masjid5jpg.jpg" class="rounded float-left masjid" alt="">
                                </div>
                                <div class="col-sm-6">
                                    <label for=""><strong>Masjid Azizi Langkat</strong></label>
                                    <label for="">Alamat : Jl. Kecamatan Tanjung Pura Kab.Langkat.</label>
                                    <hr>
                                    <small for=""><strong>Tentang</strong></small>
                                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. A distinctio. <a href="">Read more</a></p>

                                </div>

                            </div>
                        </div>
                    </div>
                    <!-- end -->

                 </div>
            </div>
        </div>
    <Footer/>

  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
export default {
    name : 'Masjid',
    components: {
        Navbar,
        Footer,
    }
}
</script>
    
<style>
    .search{
        color: white;
    }
    .masjid{
        height: 180px;
    }
</style>
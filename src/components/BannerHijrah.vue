<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
      <div class="container-fluid">
          <div class="row">
              <div class="col-lg-12 mt-5">
                  <carousel class="product-slider" :items="3" :nav="false" :autoplay="true" :dots="false" :mouseDrag="true" :touchDrag="true">
                    
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/products/women-2.jpg" alt="" />
                              <ul>
                                  <li class="w-icon active">
                                      <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                                  </li>
                                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <div class="catagory-name">Shoes</div>
                              <router-link to="/product">
                              
                                  <h5>Guangzhou sweater</h5>
                              
                              </router-link>
                              <div class="product-price">
                                  $13.00
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/products/women-3.jpg" alt="" />
                              <ul>
                                  <li class="w-icon active">
                                      <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                                  </li>
                                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <div class="catagory-name">Towel</div>
                              <router-link to="/product">
                                  <h5>Pure Pineapple</h5>
                              </router-link>
                              <div class="product-price">
                                  $34.00
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/products/women-4.jpg" alt="" />
                              <ul>
                                  <li class="w-icon active">
                                      <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                                  </li>
                                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                                  <li class="w-icon">
                                      <router-link to="/product"><i class="fa fa-random"></i></router-link>
                                  </li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <div class="catagory-name">Towel</div>
                              <router-link to="/product">
                                  <h5>Converse Shoes</h5>
                              </router-link>
                              <div class="product-price">
                                  $34.00
                              </div>
                          </div>
                      </div>
                      <div class="product-item">
                          <div class="pi-pic">
                              <img src="img/products/women-4.jpg" alt="" />
                              <ul>
                                  <li class="w-icon active">
                                      <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                                  </li>
                                  <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                                  <li class="w-icon">
                                      <router-link to="/product"><i class="fa fa-random"></i></router-link>
                                  </li>
                              </ul>
                          </div>
                          <div class="pi-text">
                              <div class="catagory-name">Towel</div>
                              <router-link to="/product">
                                  <h5>Converse Shoes</h5>
                              </router-link>
                              <div class="product-price">
                                  $34.00
                              </div>
                          </div>
                      </div>
                  </carousel>
              </div>
          </div>
      </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>

  import carousel from 'vue-owl-carousel'

  export default {
    name: "BannerHijrah",
    components: { carousel },
    
  }
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}

</style>
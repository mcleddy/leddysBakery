
<template>
    <section class="bg-light" id="products">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">products</h2>
            <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
          </div>
        </div>
        <div class="row">
          
            <div class="col-md-4 col-sm-6 products-item" v-for="(obj, key) in productsJSON" :key="key">
                <a class="products-link" data-toggle="modal" href="#productsModal2">
                    <div class="products-hover">
                        <div class="products-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="../assets/img/glazeDonut.jpg" alt="" style="height:300px">
                </a>
                <div class="products-caption">
                    <h4>Donuts</h4>
                    <p class="text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>

             <div class="col-md-4 col-sm-6 products-item" v-for="(obj, key) in productsJSON" :key="key">
                <a class="products-link" data-toggle="modal" href="#productsModal3">
                    <div class="products-hover">
                        <div class="products-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="../assets/img/cake-chocolate.jpg" alt="" style="height:300px">
                </a>
                <div class="products-caption">
                    <h4>Cakes</h4>
                    <p class="text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>

             <div class="col-md-4 col-sm-6 products-item" v-for="(obj, key) in productsJSON" :key="key">
                <a class="products-link" data-toggle="modal" href="#productsModal4">
                    <div class="products-hover">
                        <div class="products-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="../assets/img/pastries-blueberry-tart.jpg" alt="" style="height:300px">
                </a>
                <div class="products-caption">
                    <h4>Pastries & Pies</h4>
                                   <p class="text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>

             <div class="col-md-4 col-sm-6 products-item" v-for="(obj, key) in productsJSON" :key="key">
                <a class="products-link" data-toggle="modal" href="#productsModal5">
                    <div class="products-hover">
                        <div class="products-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="../assets/img/strawberry.jpg" alt=""  style="height:300px">
                </a>
                <div class="products-caption">
                    <h4>Savory Treats</h4>
                    <p class="text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>

             <div class="col-md-4 col-sm-6 products-item" v-for="(obj, key) in productsJSON" :key="key">
                <a class="products-link" data-toggle="modal" href="#productsModal6">
                    <div class="products-hover">
                        <div class="products-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="../assets/img/cookies-lemon.jpg" alt=""  style="height:300px">
                </a>
                <div class="products-caption">
                    <h4>Cookies</h4>
                    <p class="text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>


             <div class="col-md-4 col-sm-6 products-item" v-for="(obj, key) in productsJSON" :key="key">
                <a class="products-link" data-toggle="modal" href="#productsModal7">
                    <div class="products-hover">
                        <div class="products-hover-content">
                            <i class="fas fa-plus fa-3x"></i>
                        </div>
                    </div>
                    <img class="img-fluid" src="../assets/img/bread-focaccia.jpg" alt=""  style="height:300px">
                </a>
                <div class="products-caption">
                    <h4>Bread</h4>
                    <p class="text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                </div>
            </div>
        </div>
      </div>
    </section>
</template>

<script>
export default {
    data: () => ({
        productsJSON: [
            {
                img: '',
                caption: '',
                title: ''
            }
        ]
    })
}
</script>

<style lang="css">

</style>



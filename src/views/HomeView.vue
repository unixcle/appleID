<template>
  <section class="home bg-dark">
    <div class="container-fluid px-0">
      <div class="row justify-content-center mx-0">
        <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active d-md-flex">
              <div class="col-md-6">
                <img src="../assets/lop3.png" class="d-block w-50 image" alt="s">
              </div>
              <div class="col-md-6 align-self-center">
                <div class="text-white">
                  <h2 class="text-md-end">مرجع تخصصی فروش اپا آیدی</h2>
                  <ul class="ul text-md-end">
                    <li>فروش تک و عمده</li>
                    <li>بدون نات اکتیو شدن</li>
                    <li> به همراه اسم شخصی و با نام فروشگاه</li>
                  </ul>
                  <div class="text-md-end">
                    <button class="btn btn-pill btn-warning text-white mt-5 ">رفتن به صفحه محصولات</button>
                  </div>
                </div>
              </div>
            </div>
            <!-- <div class="carousel-item">
              <img src="../assets/logo.png" class="d-block w-50 image mx-0" alt="z">
            </div>
            <div class="carousel-item">
              <img src="../assets/lop3.png" class="d-block w-50 image" alt="r">
            </div> -->
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
      </div>
    </div>
  </section>
  <section id="discription" class="container-fluid">
    <div class="row justify-content-center">
      <div class="col-md-3">
        <button class="btn btn-light btn-pill mt-4 w-100 py-4 fs-3">
           تحویل فوری
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-clock" viewBox="0 0 16 16">
              <path d="M8 3.5a.5.5 0 0 0-1 0V9a.5.5 0 0 0 .252.434l3.5 2a.5.5 0 0 0 .496-.868L8 8.71V3.5z"/>
              <path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm7-8A7 7 0 1 1 1 8a7 7 0 0 1 14 0z"/>
            </svg>
        </button>
      </div>
      <div class="col-md-3">
        <button class="btn btn-light btn-pill mt-4 w-100 py-4 fs-3">
           پرداخت 
        </button>
      </div>
      <div class="col-md-3">
        <button class="btn btn-light btn-pill mt-4 w-100 py-4 fs-3">
          
          قیمت مناسب
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cash-coin" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M11 15a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm5-4a5 5 0 1 1-10 0 5 5 0 0 1 10 0z"/>
            <path d="M9.438 11.944c.047.596.518 1.06 1.363 1.116v.44h.375v-.443c.875-.061 1.386-.529 1.386-1.207 0-.618-.39-.936-1.09-1.1l-.296-.07v-1.2c.376.043.614.248.671.532h.658c-.047-.575-.54-1.024-1.329-1.073V8.5h-.375v.45c-.747.073-1.255.522-1.255 1.158 0 .562.378.92 1.007 1.066l.248.061v1.272c-.384-.058-.639-.27-.696-.563h-.668zm1.36-1.354c-.369-.085-.569-.26-.569-.522 0-.294.216-.514.572-.578v1.1h-.003zm.432.746c.449.104.655.272.655.569 0 .339-.257.571-.709.614v-1.195l.054.012z"/>
            <path d="M1 0a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h4.083c.058-.344.145-.678.258-1H3a2 2 0 0 0-2-2V3a2 2 0 0 0 2-2h10a2 2 0 0 0 2 2v3.528c.38.34.717.728 1 1.154V1a1 1 0 0 0-1-1H1z"/>
            <path d="M9.998 5.083 10 5a2 2 0 1 0-3.132 1.65 5.982 5.982 0 0 1 3.13-1.567z"/>
          </svg>
        </button>
      </div>
      <div class="col-md-3">
        <button class="btn btn-light btn-pill mt-4 w-100 py-4 fs-3">
          
            پشتیبانی آنلاین
        </button>
      </div>
    </div>
  </section>
  <section class="container mt-5">
    <div class="row">
      <div class="col-md-5 text-danger border">
        <h3 class="mt-5">{{ userName }} عزیز خوش آمدید</h3>
        <h3 class="mt-5"> نام کاربری</h3>
        <h3 class="mt-5">تغییر رمز عبور</h3>
        <h3 class="mt-5 mb-5">محصولات خریداری شده</h3>
      </div>
      <div class="col-md-6 bg-light-blue">
        <h3 class="text-danger mt-5">اپل آیدی چیست؟</h3>
        <p class="mt-3">شناسه ی اپل هم گفته شده. نوعی حساب کاربری ویژه کاربران محصولات شرکت اپل است. شرکت اپل برای حفظ حق بشر آثاری که برای سیستم های عامل و سرویس های اپل عرضه میشوند. آن ها را برچسب گإاری میکند که هر شخص تنها نتواند با مشخصات خود آن ها را نصب کند.</p>
        <img>
      </div>
    </div>
  </section>
  <section class="container mt-5" id="apple_cell">
    <div class="row justify-content-center">
      <div class="col-md-4">
        <div class="card mx-auto" style="width: 18rem;">
          <img src="../assets/sangapore.jpg" class="card-img-top border-bottom" alt="...">
          <div class="card-body">
            <h5 class="card-title">اپل آیدی سنگاپور</h5>
            <p class="card-text">
              <ul class="ul-price">
                <li> قیمت : {{ apple_1 }}</li>
              </ul>
            </p>
            <input @click="price_calc1" type="radio" class="btn-check" name="vbtn-radio" id="vbtn-radio1" autocomplete="off">
            <label class="btn btn-outline-primary" for="vbtn-radio1">Radio 1</label>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mx-auto" style="width: 18rem;">
          <img src="../assets/america.jpg" class="card-img-top border-bottom" alt="...">
          <div class="card-body">
            <h5 class="card-title">اپل آیدی آمریکا</h5>
            <p class="card-text">
              <ul class="ul-price">
                <li> قیمت : {{ apple_2 }}</li>
              </ul>
            </p>
            <input @click="price_calc2" type="radio" class="btn-check" name="vbtn-radio" id="vbtn-radio2" autocomplete="off">
            <label class="btn btn-outline-primary" for="vbtn-radio2">Radio 1</label>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mx-auto" style="width: 18rem;">
          <img src="../assets/china.jpg" class="card-img-top border-bottom" alt="...">
          <div class="card-body">
            <h5 class="card-title">اپل آیدی چین</h5>
            <p class="card-text">
              <ul class="ul-price">
                <li> قیمت : {{ apple_3 }}</li>
              </ul>
            </p>
            <input @click="price_calc3" type="radio" class="btn-check" name="vbtn-radio" id="vbtn-radio3" autocomplete="off">
            <label class="btn btn-outline-primary" for="vbtn-radio3">Radio 1</label>
          </div>
        </div>
      </div>
    </div>
    <section v-if="price" id="price" class="row justify-content-center mx-0 border-1 mt-5">
    <div class="col-12 text-center mt-4">
        <p class="mb-0 mt-5">اپل آیدی:{{ card }}</p>
        <p>قیمت:{{ price }}</p>
    </div>
    <div v-if="apple" class="p-3 d-flex justify-content-center align-items-center">
        <button @click="plus" id="plus" class="btn">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-lg" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M8 2a.5.5 0 0 1 .5.5v5h5a.5.5 0 0 1 0 1h-5v5a.5.5 0 0 1-1 0v-5h-5a.5.5 0 0 1 0-1h5v-5A.5.5 0 0 1 8 2Z"/>
            </svg>
        </button>
        <div id="numbers" style="font-family: 'Courier New', Courier, monospace;">{{ number }}</div>
        <button @click="minus" id="minus" class="btn" :disabled="end">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-dash-lg" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M2 8a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11A.5.5 0 0 1 2 8Z"/>
            </svg>
        </button>
    </div>
  </section>
  </section>
  <foot />
</template>

<script>


import price from '../components/price.vue'
import foot from '../components/footer.vue'

export default {
  name: 'HomeView',
  components: {
    price,foot
  },
  data(){
    return{
      price_active:true,
      apple_1:30000,
      apple_2:45000,
      apple_3:60000,
      price:null,
      end:false,
      apple:false,
      number:1,
      cards:['سنگاپور','آمریکا','چین'],
      card:null,
      userName:'علی'
    }
  },
  methods:{
    price_calc1(){
      this.price = this.apple_1
      this.price = this.number * this.apple_1
      this.apple = true
      if(this.number === 1){
        this.end = true
      }
      this.card = this.cards[0]
    },
    price_calc2(){
      this.price = this.apple_2
      this.price = this.number * this.apple_2
      this.apple = true
      if(this.number === 1){
        this.end = true
      }
      this.card = this.cards[1]
    },
    price_calc3(){
      this.price = this.apple_3
      this.price = this.number * this.apple_3
      console.log(this.apple_3)
      this.apple = true
      if(this.number === 1){
        this.end = true
      }
      this.card = this.cards[2]
    },
    plus(){
      this.number++
      this.price = this.number * this.price
      this.price = this.price / (this.number - 1)
      console.log(this.price)
      if(this.number !== 1){
        this.end = false
      }else{
        this.end = true
      }
      return this.number
    },
    minus(){
      this.number--
      this.price = this.price / (this.number + 1)
      this.price = this.number * this.price
      console.log(this.price)
      if(this.number !== 1){
        this.end = false
      }else{
        this.end = true
      }
      return this.number
    }
  }
}
</script>
<style>
.image{
  margin: 20px auto;
}
.ul-price{
  list-style-type: none;
}
.float{
  float: left;
}
.float-right{
  float: right;
}
.w-65{
  width: 50%;
}
.w-35{
  width: 35%;
}
.ul{
  list-style-type: square;
}
.bg-light-blue{
  background-color: aquamarine;
}
</style>
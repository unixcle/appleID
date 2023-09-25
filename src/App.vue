<template>
    <nav class="navbar navbar-expand-lg mt-5">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
          <div class="offcanvas offcanvas-end" tabindex="-1" id="navbarTogglerDemo03">
            <button  type="button" class="btn-close hide" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            <ul class="navbar-nav mb-2 mb-lg-0 vazir">
              <li class="nav-item mx-3">
                <router-link :to="{name:'home'}" class="nav-link active" aria-current="page" href="#">صفحه اصلی</router-link>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-3" href="#"> محصولات</a>
              </li>     
              <li class="nav-item">
                <a class="nav-link mx-3" href="#"> مقالات</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-3" href="#"> سوالات متداول</a>
              </li>
              <li class="nav-item">
                <a class="nav-link mx-3" href="#"> تماس با ما</a>
              </li>
            </ul>
          </div>
           <router-link to="/login"><button class="btn btn-outline-dark yek"><b> ورود | ثبت نام </b></button></router-link>
          <a class="navbar-brand" href="#">Navbar</a>
        </div>
    </nav>
  <router-view/>
</template>
<script>

export default{
  data(){
    return{
      
    }
  },
  methods:{
    
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
.hide{
    display: none;
}
@media(max-width : 990px){
    .hide{
        display: flex;
        margin:18px 18px;
        align-self: end;
    }
}
</style>

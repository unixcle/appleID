<template>
  <section id="price" class="row justify-content-center mx-0 border-1">
    <div class="col-12 text-center mt-4">
        <p class="mb-0 mt-5">اپل آیدی:</p>
        <p v-if="apple">قیمت:{{ price }}</p>
        <p v-if="!apple">قیمت:{{  }}</p>
    </div>
    <div v-if="price" class="p-3 d-flex justify-content-center align-items-center">
        <button @click="plus" id="plus" class="btn">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-lg" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M8 2a.5.5 0 0 1 .5.5v5h5a.5.5 0 0 1 0 1h-5v5a.5.5 0 0 1-1 0v-5h-5a.5.5 0 0 1 0-1h5v-5A.5.5 0 0 1 8 2Z"/>
            </svg>
        </button>
        <div id="numbers" style="font-family: 'Courier New', Courier, monospace;">{{ number }}</div>
        <button @click="minus" id="minus" class="btn">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-dash-lg" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M2 8a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11A.5.5 0 0 1 2 8Z"/>
            </svg>
        </button>
    </div>
  </section>
</template>

<script>
export default {
    props:['price','apple_1','apple_2','apple_3'],
    data(){
        return{
            number:1,
            apple:true,
            price1:30000,
            price2:45000,
            price3:60000,
            Fprice:null
        }
    },
    methods:{
        plus(){
            this.number++
            this.apple = false
            this.Fprice = price
            return this.number
        },
        minus(){
            this.number--
            this.apple = false
            console.log(this.apple)
            return this.number
        }
    },
}
</script>

<style>
.border-1{
    border: 1px blue solid;
    border-radius: 10px;
}
</style>
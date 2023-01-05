<template>
    <div class="detail">
    <div class="container">
      <h1>{{title}}</h1>
      <div class="row">
        <div class="col-md--4 col-lg-4" v-for="(data,index) in products" :key="index">
          <div v-if="proId===data.productId">
            <h1>{{data.productTitle}}</h1>
            <img :src="data.image" class="img-1">
          </div>
        </div>
      </div>
    </div>
</div>
</template>
<script>
/* eslint-disable */
  export default{
    name: 'detail',
    data () {
      return {
        proId:this.$route.params.Pid,
        title: 'detail',
        products:[
        {
          productTitle:"pizza-1",
          image:'https://media.istockphoto.com/id/1037020170/photo/homemade-pizza.jpg?s=612x612&w=is&k=20&c=5pUuBwGjXrvuGRt4k-M0ErJQJqgALzrkxdIVp5ztlFI=',
          productId:1
        },
        {
          productTitle:"pizza-2",
          image:'https://media.istockphoto.com/id/167442068/photo/deluxe-pizza-and-a-beer.jpg?s=612x612&w=is&k=20&c=WqE6O7FhTl3QadIXeyth8IBBDl-JJJr5Agjosg9Oxy0=',
          productId:2
        },
        {
          productTitle:"Burger-1",
          image:'https://media.istockphoto.com/id/1188412964/photo/hamburger-with-cheese-and-french-fries.jpg?s=612x612&w=is&k=20&c=7sOIHS_NpbI4jc7Z9nhbdnSUmgnKMPUX6aP5sslxxwQ=',
          productId:3
        },
        {
          productTitle:"Meal",
          image:'https://media.istockphoto.com/id/1295633127/photo/grilled-chicken-meat-and-fresh-vegetable-salad-of-tomato-avocado-lettuce-and-spinach-healthy.jpg?s=612x612&w=is&k=20&c=OuUGKM8o_mzG0TmcMtC6YFmMdl_tQrkLrfv7aN8Z7v8=',
          productId:4
        },
        {
          productTitle:"Dosa",
          image:'https://media.istockphoto.com/id/481750586/photo/masala-sin.jpg?s=612x612&w=is&k=20&c=AS9a9NbNtxJDayJc0irPOc_Fdn5JAt3xYnTF9Bqnadk=',
          productId:5
        },
        {
          productTitle:"Dosa",
          image:'https://media.istockphoto.com/id/1314957534/photo/spicy-masala-dosa-in-a-plate-south-indian-dish-street-food-concept-background.jpg?s=612x612&w=is&k=20&c=CDEAXKDaOQx58J9sBtToFlSwrT9jdHTzcvFvyYIqBnA=',
          productId:6
        }  
      ]
    }
  },
  }
  </script>
  <style scoped>
.detail{
  background-color: rgb(115, 80, 255);
}
.row img{
  width:300px;
  height:200px;
  border:2px solid brown;
  border-radius: 30px;
  margin-left: 0px;
}
.row h3{
  cursor:pointer;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  font-size:30px;
}  </style>
  
 
  
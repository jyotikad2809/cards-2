<template>
<div class="cards">

<div class="logo">  
     <slot name="logo"></slot>
    <button class="savedButton">saved<slot></slot></button>
        </div> 
        <div class="company">
            <h3 class="h3">{{ prop.companyName }}</h3>
            <h5 class="h5">{{ prop.day}}</h5>
        </div>
        <h1 class="title">{{ prop.title }}</h1>
        <div class="button">
            <button class="button2">{{ prop.button1 }}</button>
            <button class="button2">{{ prop.button2 }}</button>
        </div>
        <hr>
        <div class="footer">
            <div class="leftFooter">
                <h3 class="price">{{ prop.price }}</h3>
                <h5 class="h5">{{ prop.country }}</h5>
            </div>
            
            <button class="button3">{{ prop.button3 }}</button>
        </div>
</div>
</template>

<script setup>

 const prop= defineProps({
    companyName:{type:String,required:true},
    day:{type:String,required:true},
    title:{type:String,required:true},
    button1:{type:String,required:true},
    button2:{type:String,required:true},
    price:{type:String,required:true},
    country:{type:String,required:true},
    button3:{type:String,required:true},
 }
 )
</script>

<style scoped>
.cards{
    padding: 10px;
    margin: 10px;
height:315px;
width: 250px;
    display: flex;
    flex-direction: column;
    background-color: white;
    border: 2px grey;
    border-radius: 5px;
    
}
.savedButton{
    padding: 7px;
    font-weight: 400;
    border: 2px grey;
    border-radius: 5px;
    
}
.logo{
    padding: 20px;
    display: flex;
    flex-direction: row;
    
}
.company{
    display: flex;
    flex-direction: row;
    justify-content:left;
    
}
.button{
    display: flex;
    flex-direction: row;
   margin-bottom:70px;
}
.footer{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-top: 15px;
    
}
.leftFooter{
    display: flex;
    flex-direction:column;
    
    
}
.h3{
color: black;
font-weight: bold;
font-size: small;
}
.h5{
    padding:3px;
    color: grey;
    font-weight:300;
    font-size: x-small;
    
}
.title{
    color: black;
    font-size: large;
    font-weight: bolder;
    padding: 3px;
}
.button2{
    height: 23px;
    border: 20px dimgray;
    border-radius: 5px ;
    font-weight: bold;
    font-size:x-small;  
    margin-left:7px;
}
.price{
    color: black;
    font-size: large;
    font-weight: bold;
    padding: 3px;
}
.button3{
    color: white;
    background-color: black;
    font-weight: bold;
    border: 5px;
    border-radius:8px;
    width:100px;
    height:30px;

}
</style>
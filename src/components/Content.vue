<template >
   <div class="content">
<Cards v-for="item in items" 
:company-name="item.companyName"
:day="item.day"
:title="item.title"
:button1="item.button1"
:button2="item.button2"
:price="item.price"
:country="item.country"
:button3="item.button3"

>

</Cards>
</div>

</template>

<script setup>
import Cards from './Cards.vue';


const items= [{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},
{
    companyName:"Amazon",
    day:"5 days ago",
    title:"Senior UI/UXDesigner",
    button1:"Part-time",
    button2:"Senior level",
    price:"$120/hr",
    country:"SanFrancisco,CA",
    button3:"Apply now"
},



]
</script>

<style >
.content{
    background-color: dimgray;
   width:1350px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
   justify-content: space-between;

    
}
</style>

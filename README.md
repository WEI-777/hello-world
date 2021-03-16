var products=[
    {name:"cucumber",type:"vegetable",quantity:0,price:1},
    {name:"banana",type:"fruit",quantity:10,price:15},
    {name:"celery",type:"vegetable",quantity:30,price:8},
    {name:"cucumber",type:"vegetable",quantity:5,price:18},
    {name:"orange",type:"fruit",quantity:3,price:6}
];
var newProducts=products.filter(value=>value.type=="vegetable"&&value.quantity>0&&value.price<10);
console.log(newProducts);

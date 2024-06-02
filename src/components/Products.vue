<script>
export default {
    name: 'Products',
    data() {
        return {
            cards: [
                {
                    image: '/img/1.webp',
                    discount: '-50%',
                    greenflag: 'Sostenibilità',
                    marca:'Levi\'s',
                    item: 'RELAXED FIT TEE UNISEX',
                    pirce: '13,99€',  
                    oldprice: '24,99€'       
                },
                {
                    image: '/img/2.webp',
                    discount: '-30%',
                    greenflag:'',
                    marca:'Guess',
                    item: 'ROSES TEE',
                    pirce: '20,99€',  
                    oldprice: '29,99€'       
                },
                {
                    image: '/img/3.webp',
                    discount: '-30%',
                    greenflag: '',
                    marca:'Come zucchero filato',
                    item: 'VOGLIA DI COLORI PASTELLO',
                    pirce: '129,99€',  
                    oldprice: '184,99€'       
                },
                {
                    image: '/img/4.webp',
                    discount: '-50%',
                    greenflag: 'Sostenibilità',
                    marca:'Levi\'s',
                    item: 'TEE UNISEX',
                    pirce: '14,99€',  
                    oldprice: '29,99€'       
                },
                {
                    image: '/img/5.webp',
                    discount: '',
                    greenflag: '',
                    marca:'Maya Deluxe',
                    item: 'STRIPE BODICE',
                    pirce: '99,99€',  
                    oldprice: ''       
                },
                {
                    image: '/img/6.webp',
                    discount: '',
                    greenflag: 'Sostenibilità',
                    marca:'Espirit',
                    item: 'MAGLIONE - BLACK',
                    pirce: '29,99€',  
                    oldprice: ''       
                },
            ]
            
        }
    }
}
</script>

<template>
    <main class="cardlist">
            
            <div class="container">

                <div class="card">
                    <img src="/img/1.webp" alt="">
                    <div class="label">
                        <span class="discount">-50%</span>
                        <span class="greenflag">Sostenibilità</span>                        
                    </div>
                    <div class="heart">
                        <span>&hearts;</span>
                    </div>
                    <div class="description">
                        <span class="marca">Levi's</span> <br>
                        <span class="item">RELAXED FIT TEE UNISEX</span> <br>
                        <span class="price">13,99€</span> 
                        <span class="oldprice">24,99€</span>
                        
                    </div>
                </div>

                <div class="card">
                    <img src="/img/2.webp" alt="">
                    <div class="label">
                        <span class="discount">-30%</span>
                    </div>
                    <div class="heart">
                        <span>&hearts;</span>
                    </div>
                    <div class="description">
                        <span class="marca">Guess</span> <br>
                        <span class="item">ROSES TEE</span> <br>
                        <span class="price">20,99€</span> 
                        <span class="oldprice">29,99€</span>
                        
                    </div>
                </div>

                <div class="card">
                    <img src="/img/3.webp" alt="">
                   <div class="label">
                       <span class="discount">-30%</span>
                   </div>
                   <div class="heart">
                    <span>&hearts;</span>
                    </div>
                    <div class="description">
                        <span class="marca">Come zucchero filato</span> <br>
                        <span class="item">VOGLIA DI COLORI PASTELLO</span> <br>
                        <span class="price">129,99€</span> 
                        <span class="oldprice">184,99€</span>
                        
                    </div>
                </div>

                <div class="card">
                    <img src="/img/4.webp" alt="">
                    <div class="label">
                        <span class="discount">-50%</span>
                        <span class="greenflag">Sostenibilità</span>
                    </div>
                    <div class="heart">
                        <span>&hearts;</span>
                    </div>
                    <div class="description">
                        <span class="marca">Levi's</span> <br>
                        <span class="item">TEE UNISEX</span> <br>
                        <span class="price">14,99€</span> 
                        <span class="oldprice">29,99€</span>
                        
                    </div>
                </div>
                
                <div class="card">
                    <img src="/img/5.webp" alt="">
                    <div class="heart">
                        <span>&hearts;</span>
                    </div>
                    <div class="description">
                        <span class="marca">Maya Deluxe</span> <br>
                        <span class="item">STRIPE BODICE</span> <br>
                        <span class="price">99,99€</span> 
                        
                        
                    </div>
                </div>
                

                <div class="card">
                    <img src="/img/6.webp" alt="">
                    <div class="label">
                        <span></span>
                        <span class="greenflag">Sostenibilità</span>
                    </div>
                    <div class="heart">
                        <span>&hearts;</span>
                    </div>
                    <div class="description">
                        <span class="marca">Esprit</span> <br>
                        <span class="item">MAGLIONE - BLACK</span> <br>
                        <span class="price">29,99€</span> 
                    </div>
                </div>
            </div>
        </main>
</template>

<style>
.container {
    background-color: white;
    max-width: 70%;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
}

.card {
    width: calc(100% / 3);
    display: inline-block;
    padding: 10px;
    position: relative;
}

.discount {
    background-color: red;
    padding: 5px;
    color: white;
}

.greenflag {
    background-color: green;
    color: white;
    padding: 5px;
}

.card > .label {
    position: absolute;
    bottom: 120px;
    left: 10px;
}

.card > .heart{
   position: absolute;
   top: 30px;
   right: 10px;
}

.heart {
    font-size: 40px;
    background-color: white;
    width: 40px;
    height: 40px;
    text-align: center;
}

.marca {
    font-size: 15px;
}

.item {
    font-weight: bold;
}

.price {
    color: red;
}

.oldprice {
    text-decoration: line-through;
    font-size: 13px;
}
</style>
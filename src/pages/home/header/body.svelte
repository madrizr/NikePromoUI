<script>
    import Circle from "../../../shared/circle.svelte";
</script>
<section class="grilla">
    <div class="container" style="grid-column: span 2 / span 2;">
        <div>
            <h1 class="text-title">Nike</h1>
            <h2 class="text-title dynamic">Dynamic-F9</h2>
        </div>
        <div  class="description">
            <p class="text-normal">Shoes as unique as the human who wears it like nike</p>
        </div>
        <div class="container-button">
            <button class="button">Buy Now</button>
            <p class="price text-normal">$ 120</p>
        </div>
    </div>
    <div  class="tennis-container" style="position: relative;">
        <div class="tennis">
            <img src="/assets/tennis.png" alt="nike-dynamic" style="width: 100%; height: 100%; object-fit: cover;">
        </div>
        <Circle />
    </div>
</section>

<style>
    .description{
        margin: 2.5rem 0;
    }
    .container-button{
        display: flex;
    }
    
    .grilla{
        display: grid;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        padding: 2rem 6rem 0 6rem;
        height: 30rem;
    }
    .tennis{
        height: 50rem;
        width: 49.375rem;
        position: absolute;
        right: 3px;
        top: 0px;
        left: -290px;
        bottom: 0px;
        margin: auto;
        z-index: 1;  
    }
    .price{
        font-weight: bold;
        margin: 1rem 1.5625rem;
    }
    .dynamic{
        background: linear-gradient(90deg, #8F2EFF 1.4%, #2DC7D9 100%);
        margin: 0;
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    @media (max-width: 1290px){
        .tennis-container{
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .grilla{
            display: block;
            padding:0;
            height: auto;
            padding: 2.5rem 1rem 0 1rem;
        }
        .container-button{
            justify-content: center;
            flex-direction: column;
        }
        .price{
            font-weight: bold;
            margin: 1rem 0;
            text-align: center;
        }
        .tennis{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 27rem;
            width: 40rem;
            position:unset;
            z-index: 1;
        }
    }
</style>
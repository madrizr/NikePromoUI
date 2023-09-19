<script>
    import Circle from "../../../shared/circle.svelte";

</script>
<section class="grilla">
    <div style="grid-column: span 2 / span 2;">
        <div>
            <h1 class="text-title">Nike</h1>
            <h2 class="text-title dynamic">Dynamic-F9</h2>
        </div>
        <div class="text-normal" style="margin: 2.5rem 0;">
            <p>Shoes as unique as the human who wears it like nike</p>
        </div>
        <div style="display: flex;">
            <button class="button">Buy Now</button>
            <p class="price text-normal">$ 120</p>
        </div>
    </div>
    <div  class="tennis-container" style="position: relative;">
        <div class="tennis">
            <img src="/assets/tennis.png" alt="nike-dynamic" style="width: 100%; height: 100%; ">
        </div>
        <Circle />
    </div>
</section>

<style>
    .tennis-container{
        display: flex;
        justify-content: center;

    }
    .grilla{
        display: grid;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        padding: 2rem 6rem 0 6rem;
        overflow-x: unset;
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
</style>
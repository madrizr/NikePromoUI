<div class="elipse"></div>
<div class="elipse-blur">
    <div class="elipse_blue"></div>
    <div class="elipse_purpure"></div>
    <div class="elipse_blue-black"></div>
</div>


<style>
    .elipse{
        position: absolute;
        width: 20rem;
        height: 20rem;
        flex-shrink: 0;
        border-radius: 32.625rem;
        opacity: 0.05;
        background: radial-gradient(50% 50% at 50% 50%, rgba(255, 255, 255, 0.00) 0%, #FFF 100%);
    }
    .elipse-blur{
        filter: blur(125px);
        position: absolute;
    }
    .elipse_blue{
        border-radius: 20.73931rem;
        background: #2DC7D9;
        width: 10rem;
        height: 10rem;
        flex-shrink: 0;
    }
    .elipse_purpure{
        border-radius: 20.73931rem;
        background: #9C0C97;
        width: 10rem;
        height: 10rem;
        flex-shrink: 0;
    }
    .elipse_blue-black{
        width: 10rem;
        height: 10rem;
        flex-shrink: 0;
        border-radius: 20.73931rem;
        background: #2D136A;
    }
</style>
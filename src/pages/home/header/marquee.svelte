<script>
    import Marquee from "../../../shared/marquee.svelte";

</script>
<section class="section-marquee">
    <Marquee />
    <div class="marquee">
        <div class="marquee-wrapper">
            <div class="text-marquee">
                <span>Air jordan</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 17 17" fill="none">
                    <path d="M9.31016 0.41014L9.95802 7.1588L16.4196 9.211L9.67099 9.85887L7.61878 16.3205L6.97091 9.57184L0.509294 7.51963L7.25795 6.87176L9.31016 0.41014Z" fill="white"/>
                </svg>
                <span>Air max</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 17 17" fill="none">
                    <path d="M9.31016 0.41014L9.95802 7.1588L16.4196 9.211L9.67099 9.85887L7.61878 16.3205L6.97091 9.57184L0.509294 7.51963L7.25795 6.87176L9.31016 0.41014Z" fill="white"/>
                </svg>
                <span>Yeezy</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 17 17" fill="none">
                    <path d="M9.31016 0.41014L9.95802 7.1588L16.4196 9.211L9.67099 9.85887L7.61878 16.3205L6.97091 9.57184L0.509294 7.51963L7.25795 6.87176L9.31016 0.41014Z" fill="white"/>
                </svg>
                <span>Originals</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 17 17" fill="none">
                    <path d="M9.31016 0.41014L9.95802 7.1588L16.4196 9.211L9.67099 9.85887L7.61878 16.3205L6.97091 9.57184L0.509294 7.51963L7.25795 6.87176L9.31016 0.41014Z" fill="white"/>
                </svg>
                <span>Originals</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 17 17" fill="none">
                    <path d="M9.31016 0.41014L9.95802 7.1588L16.4196 9.211L9.67099 9.85887L7.61878 16.3205L6.97091 9.57184L0.509294 7.51963L7.25795 6.87176L9.31016 0.41014Z" fill="white"/>
                </svg>
                <span>Air Nike</span>
            </div>
        </div>
    </div>
    
</section>

<style>
.text-marquee{
    margin-right: 1.5rem;
    float: left;
    transform: translateX(-500px);
}
.text-marquee span{
    margin: 0 2rem;
    color: #FFF;
    font-family: Montserrat;
    font-size: 1.625rem;
    font-style: normal;
    font-weight: 600;
    line-height: 160%; /* 2.6rem */
    letter-spacing: 0.065rem;
    text-transform: capitalize;
    text-transform: uppercase;
}
.section-marquee{
    position: relative;
    width: 100%;
    height: 250px;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
}

.marquee{
    position: absolute;
    width: 120%;
    padding: .5rem 0;
    overflow: hidden;
    background: #181924;
    transform: rotate(6.068deg) translateX(-100px);
    margin: 5rem 0 0 0; 
    top: 0px; 
    
}

.marquee-wrapper{
    animation: marqueeAnimation 25s linear 0s infinite; 
}

/* ---------------- ANIMACION ------------------- */

@keyframes marqueeAnimation{
    100%{
        transform: translateX(2000px);
    }
}
 /* ------------- Animacion Responsive -----------------*/

 @media (max-width: 1320px){
    .marquee{
    width: 1400px;
    padding: 0;
    text-align: center;
    overflow: hidden;
    background: #181924;
    transform: rotate(8.068deg) translateX(-5px);
    margin: 4rem 0;
      
}
.text-marquee{
    margin-right: 0rem;
    float: left;
    transform: translateX(-800px);
}
.marquee .text-marquee{
    color: #FFF;
    font-family: Montserrat;
    font-size: 1rem;
}
.marquee-wrapper{
    animation: marqueeAnimation 15s linear 0s infinite; 
}
 }
</style>
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

<style>
    .text-marquee{
        display: flex;
        flex-wrap: nowrap;
        justify-content: center;
        align-items: center;
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

.marquee{
    position: absolute;
    width: 120%;
    padding: .5rem;
    overflow: hidden;
    background: #7CC402;
    transform: rotate(-6.068deg) translateX(-100px);
    position: absolute;
    top: 95px;
}

.marquee-wrapper{
    animation: marqueeAnimation 10s linear 0s infinite; 
}

.marquee .text-marquee{
    margin-right: 1.5rem;
    float: left;
    transform: translateX(-500px);
}

/* ---------------- ANIMACION ------------------- */

@keyframes marqueeAnimation{
    100%{
        transform: translateX(2000px);
    }
}
 /* ------------- Animacion Responsive -----------------*/

 @media (max-width: 992px){
    .marquee{
    width: 110%;
    padding: .5rem;
    text-align: center;
    overflow: hidden;
    background: #181924;
    transform: rotate(5.068deg) translateX(-5px);
    margin: 4rem 0;  
}
.marquee .text-marquee{
    color: #FFF;
    font-family: Montserrat;
    font-size: 1rem;
}
 }
</style>
<section class="grilla text-normal">
    <a href="https://nike.com" target="_blank">
        <img src="/logo.svg" alt="">
    </a>
    <div class="menu">
        <span>Shop</span>
        <span>Home</span>
        <span>Contact</span>
    </div>
    <a href="google.com" target="_blank" class="user">
        <img src="/assets/icon-user.svg" alt="" style="width: 1.5rem; height: 1.5rem">
    </a>
</section>

<style>
    .menu span:nth-child(1){
        opacity: 1;
    }
    span{
        cursor: pointer;
        opacity: .5;
        transition: .3s;
    }
    span:hover{
        opacity: 1;
        transition: .3s;
    }
    .user{
        display: flex;
        justify-content: end; 
        z-index: 1000; 
    }
    .grilla{
        display: grid;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        padding: 2rem 6rem;
    }
    .menu{
        display: flex;
        justify-content: space-between;
        z-index: 1000;
    }
    @media (max-width: 900px){
        .grilla{
            display: none;
        }
    }
</style>
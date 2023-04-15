<template>
    <div class = "root h-full">
        <div id = "navC" class="body h-full">
            <button class ="burger" @click="toggleMenu"></button>
            <div class="background"></div>
            <div class="menu">
                <nav>
                    <a style="animation-delay:0.2s" href="">
                        About
                    </a>
                    <a style="animation-delay:0.2s" href="">
                        About
                    </a>
                    <a style="animation-delay:0.2s" href="">
                        About
                    </a>
                    <a style="animation-delay:0.2s" href="">
                        About
                    </a>
                </nav>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    methods:{
        toggleMenu(){
            document.getElementById("navC").classList.toggle("open")
        }
    }
}
</script>
<style lang="css">
    .burger,
    .menu,
    .background{
        position:fixed
    }
    .burger{
        z-index:4;
        top:0;
        left:0;
        display:grid;
        place-items: center;
        width:88px;
        height:88px;
        background-color: #ee0044;
        /* background: url("../assets/menu.png"); */
        background-repeat:no-repeat;
        background-position: center;
    }
    .background{
        position:fixed;
        z-index:2;
        top:44px;
        left:44px;
        aspect-ratio: 1/1;
        translate: -50%, -50%;
        height:88px;
        background:#07030a;
        border-radius: 50%;
        transform: 0.6s;
        opacity:0;
    }
    .body.open .background{
        height:300vh;
        opacity: 0.8;
    }
    .body.open .menu{
        opacity: 1;
        visibility: visible;
    }
    .menu{
        z-index:3;
        top:0;
        left:0;
        display:flex;
        align-items:center;
        height:100%;
        width:100%;
        transition:0.05s;
    }
    .body .menu nav:hover > a{
        opacity:0.25;
    }
    .body .menu nav > a:hover{
        opacity:1;
        translate: 8px 0;
    }
    .menu nav{
        display:flex;
        flex-direction:column;
        justify-content: center;
        align-items: flex-start;
        padding-left: 100px;
    }
    .menu a{
        position:relative;
        color:#f9f9f9;
        font-size: 32px;
        padding:20px 0px 20px 20px;
        text-decoration: none;
        opacity: 0;
        transition: 0.4s;
    }
    .menu a::after{
        content: "";
        position:absolute;
        top:50%;
        right: -26px;
        translate: 0 -50%;
        width:10px;
        height:10px;
        border-top: 3px solid #ffffff;
        border-right: 3px solid #ffffff;
        opacity:0;
        rotate: 45deg;
        transition: 0.3s;
    }
    .menu a:hover::after{
        opacity:1;
    }
    @keyframes appear{
        0%{
            opacity:0;
            translate:-30px 0;
        }
        100%{
            opacity:1;
        }
    }
    .body.open .menu a{
        opacity:1;
        animation: appear 0.35s backwards;
    }
</style>
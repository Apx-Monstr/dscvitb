<template>
    <div class = "inter text-[1.1rem] duration-700">
        <Header/>
        <Nuxt/>
        <Footer/>
    </div>
</template>

<script>
export default {
    head(){
        return {
            script:[
                {
                    src:"https://cdn.tailwindcss.com"
                },
            ]
        }
    },
}
</script>
<style >
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
    ::-webkit-scrollbar {
  width: 8px;
  border-radius:10px;
}
 
::-webkit-scrollbar-track {
  background-color:#ffffff;
}
 
::-webkit-scrollbar-thumb {
  background-color: #6c36d3;
  border-radius: 1px;
}
    .inter{
        font-family: 'Poppins', sans-serif;
    }
    .prim{
        background-color: #6c36d3;
    }
    .prim2{
        background-color: rgb(37, 150, 190);
    }
    .sec{
        background-color:#000000;
    }
    .white{
        background-color:#ffffff;
    }
    .dark{
        background-color:#1f094e;
    }
    .textdark{
        color:#1f094e;
    }
    .textW{
        color:#ffffff;
    }
    .textPrim{
        color:#6c36d3;
    }
    .textB{
        color:#000000;
    }

</style>
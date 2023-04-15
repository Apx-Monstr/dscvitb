<template>
    <div class = "h-16 flex">
        <img v-if="color === 'white'" src = "@/assets/middle-removebg.png">
        <img v-else src= "@/assets/middle-removebg.png">
    </div>
</template>

<script>
export default {
    props:{
        size:{
            default:"h-16",
            type:String,
        },
        color:{
            default:"black",
            type:String,
        }
    },
}
</script>
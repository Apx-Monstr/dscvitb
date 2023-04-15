<template>
    <div class = "textPrim py-2 text-left">
        {{text}}
    </div>
</template>

<script>
export default {
    props:{
        text:{
            default:"Ehlloo",
            type:String,
        }
    }
}
</script>
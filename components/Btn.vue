<template>
    <button v-if="mode==='color'" class = "rounded prim textW px-5 py-1">
        {{text}}
    </button>
    <button v-else-if="mode==='white'" class = "textB px-5 py-1 hover:text-[#6c36d3]">
        {{text}}
    </button>
</template>

<script>
export default {
    props:{
        text:{
            default:"Hello",
            type:String
        },
        mode:{
            default:"white",
            type:String,
        }
    },
}
</script>
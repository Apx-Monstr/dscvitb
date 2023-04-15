<template>
    <div class = "w-full  scroll-smooth overflow-hidden">
        <div class="-z-20 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] h-[200vh] w-[150vw] fixed -top-[500px] -left-[500px] rotate-12"></div>

        <div class="h-[100vh] z-10 rounded overflow-auto grid place-items-end justify-items-center overflow-hidden text-6xl textW">
            Events
            <div class="w-[90vw] bg-blue-600 rounded h-[80vh] overflow-y-auto">
                <div class="overflow-auto">
                    <div class="h-[80vh] bg-red-600">
                        Hi
                    </div>
                    <div class="h-[80vh] bg-red-600">
                        Hi
                    </div>
                </div>
            </div>
        </div>
        <div class="grid place-content-center text-xl absolute bottom-4 w-full">
            <div class="white text-slate-900 p-4 rounded">
                <nuxt-link to = "/">
                    <Btn text = "Home"/>
                </nuxt-link>
                <nuxt-link to = "">
                    <Btn text = "Blog"/>
                </nuxt-link>
                <nuxt-link to = "/about">
                    <Btn text = "About"/>
                </nuxt-link>
                <nuxt-link to = "/event">
                    <Btn text = "Event"/>
                </nuxt-link>
            </div>
        </div>
        <div class="relative">
            
        </div>
        
    </div>
</template>

<script>
export default {
    layout:"full",
    head(){
        return {
            title: "Events | TedxVitBhopal",
        }
    },
}
</script>

<style>

</style>
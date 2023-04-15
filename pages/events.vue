<template>
    <div class = "w-full  scroll-smooth overflow-hidden">
        <div class="-z-20 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] h-[200vh] w-[150vw] fixed -top-[500px] -left-[500px] rotate-12"></div>

        <div class="h-[100vh] z-10 rounded overflow-auto grid place-items-end justify-items-center overflow-hidden text-6xl textW">
            Events
            <div class="w-[90vw] rounded h-[80vh] overflow-y-auto">
                <div class="overflow-auto snap-y snap-mandatory scroll-smooth">
                    <div class="snap-start relative contrast-125 h-[80vh] w-full p-4 rounded-lg bg-cover bg-center bg-[url('https://images.unsplash.com/photo-1560523159-4a9692d222ef?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTB8fHRlZCUyMHRhbGt8ZW58MHx8MHx8&auto=format')]" id="eve1" role="tabpanel" aria-labelledby="eve1-tab">
                        <div class="absolute textW text-4xl font-bold">
                            <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                            <p class = "text-sm textPrim">
                                20TH DECEMBER 2022
                            </p>
                            ML SPRINT
                        </div>
                    </div>
                    <div class="snap-start relative contrast-125 h-[80vh] w-full p-4 rounded-lg bg-cover bg-center bg-[url('https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress')]" id="eve1" role="tabpanel" aria-labelledby="eve1-tab">
                        <div class="absolute textW text-4xl font-bold">
                            <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                            <p class = "text-sm textPrim">
                                10TH OCTOBER 2022
                            </p>
                            ML BOOTCAMP
                        </div>
                    </div>
                    <div class="snap-start relative contrast-125 h-[80vh] w-full p-4 rounded-lg bg-cover bg-center bg-[url('https://images.unsplash.com/photo-1635002962487-2c1d4d2f63c2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mjl8fG1ldGF2ZXJzZXxlbnwwfHwwfHw%3D&auto=format')]" id="eve1" role="tabpanel" aria-labelledby="eve1-tab">
                        <div class="absolute textW text-4xl font-bold">
                            <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                            <p class = "text-sm textPrim">
                                10 AUGUST
                            </p>
                            DSA DASH
                        </div>
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
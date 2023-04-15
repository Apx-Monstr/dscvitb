<template>
    <div class="  sec textW  py-24 text-2xl">
        <div class="m-auto max-w-screen-xl flex justify-center items-center">
            <div class="flex flex-col items-center content-center flex-1">
                <div>
                    
                    <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                    Register Now
                </div>
                <p class = "text-5xl font-bold textPrim pt-2">
                    ADVITYA 2023
                </p>
                <p v-if="para" class = "text-base pb-8 pt-2 text-center" >
                    {{para}}
                </p>
                <p v-else class = "text-base pb-8 pt-2 text-center">
                    The Most Awaited event of the year is here <br> DSC | VITB presents the scinthilating event on April 23, 2022.
                </p>
                <nuxt-link to="/advitya2023">
                    <Btn text= "Register Now" mode="color" class = "px-6 py-3"/>
                </nuxt-link>
            </div>
            <div class=" flex gap-6 items-center justify-center origin-center -rotate-12  flex-1">
                <div class="w-32 h-56">
                    <div class="h-full w-full rounded-md bg-center bg-cover bg-[url('https://images.unsplash.com/photo-1488229297570-58520851e868?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTd8fGRhdGElMjBzY2llbmNlfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60')]">
                        
                    </div>
                </div>
                <div class="w-32 h-80">
                    <div class="h-full w-full rounded-md bg-center bg-cover bg-[url('https://image.lexica.art/full_jpg/036d9d30-7650-4264-9569-49a259061982')]">
                        
                    </div>

                </div>
                <div class="w-32 h-56">
                    <div class="h-full w-full rounded-md bg-center bg-cover bg-[url('https://images.unsplash.com/photo-1542903660-eedba2cda473?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fGRhdGElMjBzY2llbmNlfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60')]">
                        
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

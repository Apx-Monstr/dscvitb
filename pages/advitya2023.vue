<template>
    <div class = "w-full">
        <ComingEvent/>
        <div class = "h-[90vh] w-full">
            <div class="m-auto max-w-screen-xl h-full w-full grid items-center">
                <div class="h-[75%] flex rounded">
                    <div class="flex-1 overflow-hidden">
                        <div class="h-full prim w-[90%] -skew-x-12">
                        </div>
                    </div>
                    <div class="flex-1 grid place-items-center">
                        <div class = "flex w-full gap-4 p-8 flex-col">
                            <h1 class="text-3xl">
                                <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                                Register !
                            </h1>
                            Fill in the details below to register <br>for the most awaited event of 2023
                            <Input text="Name" placeholder = "Full Name"/>
                            <Input text = "Email" placeholder = "abc@vitbhopal.ac.in"/>
                            <div class="grid place-items-start py-4">
                                <Btn text="Register" mode = "color" class = "px-6 py-3"/>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
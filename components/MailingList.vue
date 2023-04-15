<template>
    <div class="text-slate-900 py-24 text-2xl">
        <div class="m-auto max-w-screen-xl flex flex-col justify-center items-center gap-10">
            <div class="text-4xl text-slate-900">
                <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                Mailing List
            </div>
            Heyy, why dont you join our mailing list and get updates right in your inbox... Join Now
            <div class="w-[50%] flex flex-col gap-6">
                <Input/>
                <Input text="Email" placeholder = "abc@vitbhopal.ac.in"/>
            </div>
            <div>
                <Btn mode = "color" text = "Join Now" class = "px-6 py-3"/>
            </div>
        </div>
    </div>
</template>
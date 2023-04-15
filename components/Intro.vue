<template>
    <div class="text-slate-900 py-24 text-2xl">
        <div class="m-auto max-w-screen-xl flex justify-center items-center gap-10">
            <div class=" flex gap-6 items-center justify-center origin-center flex-1 m-2">
                <div class="w-full aspect-[1/1] flex bg-cover bg-center brightness-75 contrast-125 bg-[url('https://images.pexels.com/photos/401107/pexels-photo-401107.jpeg?auto=compress')]">
				</div>
            </div>
            <div class=" flex-1 p-3">
                <div class="h-1 w-24 bg-gradient-to-r from-[#6c36d3] to-[#1f094e] my-2"></div>
                <h3 class = "text-4xl pb-6">Who we Are</h3>
                <p class="p-1 text-xl pb-10">
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repellendus, voluptatibus? Voluptates dolorum mollitia corrupti error ut. Quos obcaecati totam voluptatem corporis officiis! Eaque accusantium odio sed molestiae velit? Voluptas, eaque.
                </p>
                <nuxt-link to = "/about">
                    <Btn mode = "color" class = "px-6 py-3" text="Visit Team"/>
                </nuxt-link>
            </div>
        </div>
    </div>
</template>

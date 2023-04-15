<template>
    <div class = "h-[80px] sticky top-0 white z-50 w-full border-b-2">
        <div class="m-auto max-w-screen-xl h-full w-full grid items-center">
            <div class="flex w-full justify-between">
                <Logo/>
                <div class="flex gap-3 py-3">
                    <nuxt-link to = "">
                        <Btn text="Blog"/>
                    </nuxt-link>
                    <nuxt-link to = "/about">
                        <Btn text="About"/>
                    </nuxt-link>
                    <nuxt-link to = "/events">
                        <Btn text="Events"/>
                    </nuxt-link>
                    <nuxt-link to = "">
                        <Btn text="Register" mode = "color"/>
                    </nuxt-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:"Header"
}
</script>
<script>
    export default {
        props: {
            title: String,
            text: String,
            layout: String
        }

    }
</script>

<template>
    <div class="relative bg-[url('../assets/banner1.jpg')] bg-cover ">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent to-black" style="opacity: 0.6"></div>
        <div :class="{'flex flex-row-reverse' : layout == 'right'}" class=" relative z-10 w-3/4 mx-auto text-white py-40">
            <div class="inner-content md:w-1/3 w-2/3 ">
                <h2 class="text-6xl">{{ title }}</h2>
                <p class="my-4">{{ text }}</p>
                <button class="transition btn border border-white p-2 rounded font-bold hover:bg-white hover:text-black ">Shop Merch</button>
            </div>
        </div>
    </div>
</template>
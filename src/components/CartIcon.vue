<script>
    export default {

        data() {
            return {
                count: 5
            }
        },

        methods: {
            clickIcon() {
                this.count++
            }
        }

    }

</script>

<template>
    <div @click="clickIcon" class="cart relative bg-black p-1 w-14 rounded-lg">
        <div class="counter rounded-full absolute -right-2 -top-2 text-black bg-white w-6 text-center">{{ count }}</div>
        <img class="w-6 h-6 mx-auto" src="../assets/cart.svg" alt="">
    </div>
</template>
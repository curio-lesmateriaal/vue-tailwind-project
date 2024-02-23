<script></script>

<template>
    <div class="bg-primary p-2">
        <div class="container md:w-3/4 mx-auto flex justify-between items-center">
            <div class="logo">
                <img src="../assets/logo.svg" alt="">
            </div>
            <div class="menu text-white flex gap-4 items-center">
                <ul class="navbar flex gap-8 p-4">
                    <li class=""><a href="#">Home</a></li>
                    <li class=""><a href="#">About</a></li>
                    <li class=""><a href="#">Shop</a></li>
                    <li class=""><a href="#">Donate</a></li>
                    <li class=""><a href="#">Contact</a></li>
                </ul>
                <div class="cart relative bg-black p-1 w-14 rounded-lg">
                    <div class="counter rounded-full absolute -right-2 -top-2 text-black bg-white w-6 text-center">0</div>
                    <img class="w-6 h-6 mx-auto" src="../assets/cart.svg" alt="">
                </div>
            </div>
            
        </div>
    </div>
</template>
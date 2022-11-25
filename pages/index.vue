<template>
    <main>
        <section class=" flex items-center justify-center gap-[70px] text-white !py-[100px] bg-[#000]">
            <div class="w-[45%]">
                <h1 class="text-[70px] font-bold leading-[5rem]">Lorem ipsum <span
                        class="text-[white] hover:text-[gold]">Waffles</span> sit amet.</h1>
                <p class="text-[18px] leading-[2.5rem] py-[2rem]">Lorem ipsum dolor sit amet, consectetur adipisicing
                    elit.
                    Illum vel
                    dolorem excepturi assumenda amet
                    saepe
                    vero illo asperiores quae, ullam ipsa numquam modi sapiente vitae qui quisquam ipsam accusantium
                    corporis
                    commodi? Sunt ratione, veritatis nam dolores, laborum fugit alias officia in nobis odit cupiditate
                    quibusdam
                    facilis sapiente quisquam magni voluptas!</p>
                <button
                    class="bg-[yellow] px-[32px] py-[16px] text-black rounded-md hover:text-[white] hover:bg-[#333333] duration-300">Shop
                    Now</button>
            </div>

            <div>
                <img class="w-[480px] object-cover rounded-lg" src="../assets/wafflesbg2.jpg" alt="">
            </div>
        </section>
        <section class=" flex flex-row-reverse items-center justify-center gap-[70px] !py-[100px] bg-[#D2AC31]">
            <div class="w-[45%]">
                <h1 class="text-[70px] font-bold leading-[5rem]">Lorem ipsum <span
                        class="text-[white] hover:text-[gold]">Waffles</span> sit amet.</h1>
                <p class="text-[18px] leading-[2.5rem] py-[2rem]">Lorem ipsum dolor sit amet, consectetur adipisicing
                    elit.
                    Illum vel
                    dolorem excepturi assumenda amet
                    saepe
                    vero illo asperiores quae, ullam ipsa numquam modi sapiente vitae qui quisquam ipsam accusantium
                    corporis
                    commodi? Sunt ratione, veritatis nam dolores, laborum fugit alias officia in nobis odit cupiditate
                    quibusdam
                    facilis sapiente quisquam magni voluptas!</p>
                <button
                    class="bg-[yellow] px-[32px] py-[16px] rounded-md hover:text-[white] hover:bg-[black] duration-300">Shop
                    Now</button>
            </div>

            <div>
                <img class="w-[480px] object-cover rounded-lg" src="../assets/wafflesbg.jpg" alt="">
            </div>
        </section>
    </main>
</template>

<script setup>
definePageMeta({
    title: 'My home page',
})
useHead({
    title: 'Waffles',
    
})
</script>

<style scoped>
section{
    padding: 0 200px;
}
</style>

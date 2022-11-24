<template>

    <nav ref="navigation"
        class="flex sticky top-0 px-[100px] justify-between py-[1rem] z-10 bg-[white] ease-in-out duration-300 x-[1.5rem] items-center">
        <div class="">
            <img class="w-[60px]" src="../assets/waffleslogo4.png" />
        </div>
        <div class="flex gap-[30px]">
            <p>About</p>
            <p>Service</p>
            <p>Menu</p>
            <p>Shop</p>
        </div>
    </nav>

</template>

<script setup lang="ts">
const navigation = ref()
onMounted(() => {
    console.log(navigation.value.classList);

    window.addEventListener('scroll', () => {
        if (window.scrollY > 10) {
            // navigation.value.classList.remove('bg-[white]')
            navigation.value.classList.add('!bg-[red]')
            navigation.value.classList.add('!py-[.5rem]')

        }
        else {
            navigation.value.classList.remove('!bg-[red]')
            navigation.value.classList.remove('!py-[.5rem]')
        }

    })
})

</script>

<style scoped>

</style>

<template>
    <div class="mt-[20vh]">
        <div class="flex justify-center">
            <h1 class="tracking-tight text-2xl font-semibold">De volleybaas is:</h1>
        </div>
        <div class="flex justify-center">
            <h2 class="tracking-tight text-4xl font-bold"> {{ volleybaas }}</h2>
        </div>
        <div class="flex justify-center">
            <img class="mt-10 w-[60%]" :src="'/img/' + volleybaas + '.jpg' " alt="Volleybaas">
        </div>
    </div>
</template>

<script>
export default {
    name: "Home",
    props: {
        volleybaas: String,
    }
}
</script>

<style scoped>

</style>

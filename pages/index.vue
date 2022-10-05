<template>
    <div class="flex items-center justify-center w-full h-screen">


        <div class="flex flex-col mt-20">
            <div class="text-center"> login</div>
            <label class="mt-2 flex flex-col">
                email
                <input type="text"
                    class="py-2 placeholder-gray-400 rounded-lg border border-red-400 hover:outline-none focus:outline-none"
                    placeholder="email">
            </label>
            <label class="mt-2 flex flex-col">
                password
                <input
                    class="py-2 placeholder-gray-400 rounded-lg border border-red-400 hover:outline-none focus:outline-none"
                    type="text" placeholder="password">
            </label>
            <nuxt-link to="/login" class="text-center mt-2 text-white bg-red-400 py-2 rounded-xl">Login</nuxt-link>
        </div>

    </div>
</template>

<script>

</script>

<style>

</style>
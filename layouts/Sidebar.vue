<template>
    <div>
        <div class="drawer drawer-end">
            <input id="my-drawer-4" type="checkbox" class="drawer-toggle" />
            <div class="drawer-content">
                <!-- Page content here -->
                <div class="w-full bg-black p-3">
                    <label for="my-drawer-4" class="drawer-button">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-6 h-6 text-white">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                        </svg>
                    </label>
                </div>
                <div>
                    <NuxtPage />
                </div>
            </div>
            <div class="drawer-side">
                <label for="my-drawer-4" class="drawer-overlay"></label>
                <ul class="menu p-4 overflow-y-auto w-80 bg-base-100 text-base-content">
                    <!-- Sidebar content here -->
                    <li>
                        <nuxt-link to="/dashboard">خانه </nuxt-link>
                    </li>
                    <li><a>فروشگاه</a></li>
                </ul>
            </div>
        </div>

    </div>
</template>
<script>
export default {

}
</script>

<style>

</style>
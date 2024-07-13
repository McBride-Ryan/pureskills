<template>
    <div class="font-sans antialiased z-50 border-b border-gray-200 bg-white" id="app">
        <nav class="flex items-center justify-between flex-wrap bg-teal p-6">
            <div class="flex items-center flex-no-shrink mr-6">
                <routerLink to="/">
                    <img src="/PureSkillsLogo.png" width="54" height="54" alt="" srcset="">
                </routerLink>
                <routerLink to="/">
                    <span class="font-semibold text-xl tracking-tight">Pure Skills Hoops</span>
                </routerLink>
            </div>
            <div class="block sm:hidden">
            <button @click="toggle" class="flex items-center px-3 py-2 border rounded text-teal-lighter border-teal-light hover:underline hover:border-white">
                <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
            </button>
            </div>
            <div :class="open ? 'block': 'hidden'" class="w-full flex-grow sm:flex sm:items-center sm:w-auto">
            <div class="text-sm sm:flex-grow">
                <routerLink to="/camps" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-teal-lighter hover:underline mr-4">
                    Camps
                </routerLink>
                <routerLink to="/clinics" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-teal-lighter hover:underline mr-4">
                    Clinics
                </routerLink>
                <routerLink to="/training" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-teal-lighter hover:underline mr-4">
                    Training
                </routerLink>
                <routerLink to="/team" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-teal-lighter hover:underline">
                    Our Team
                </routerLink>
            </div>
            <div>
                <a href="https://forms.gle/GjhzpZBW2aDXQHVv9" target="_blank" class="hidden sm:flex text-sm px-4 py-2 bg-blue-600 font-bold text-white rounded hover:text-teal hover:bg-blue-400 mt-4 sm:mt-0">Get Started</a>
            </div>
            </div>
        </nav>
    </div>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
export default {
    name: 'Navbar',
    data(){
        return {
            open: false,
        }
    },
    methods: {
        toggle() {
            this.open = !this.open
        }
    }
}
</script>
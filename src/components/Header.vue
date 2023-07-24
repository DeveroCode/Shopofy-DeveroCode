<template>
    <header class="grid grid-cols-12 gap-5 max-w-7xl mt-5">
        <div class="col-span-8 flex flex-1">
            <div class="flex items-center">
                <!-- Icon -->
                <img src="../../public/favicon.png" alt="icon" class="w-16">
                <h2 class="font-semibold text-2xl ml-2">.Devero</h2>
                <nav class=" ml-44 flex space-x-6">
                    <a href="#" class="text-gray-500 hover:text-black duration-300">Apps</a>
                    <a href="#" class="text-gray-500 hover:text-black duration-300">Themes</a>
                    <a href="#" class="text-gray-500 hover:text-black duration-300">Custom storefonts</a>
                    <a href="#" class="text-gray-500 hover:text-black duration-300">Marketplaces</a>
                </nav>
            </div>
        </div>
        <div class="col-span-4 flex items-center space-x-5">
            <!-- Search -->
            <div>
                <input type="text"
                    class="py-1 shadow px-5 borsder border-gray-200 rounded-full mt-1 focus:border-gray-500 focus:outline-none"
                    placeholder="Search">
            </div>
            <!-- Other Options -->
            <nav class="space-x-4">
                <!-- Icon Dark -->
                <a href="#" class="text-gray-500 hover:text-black duration-300">Dark</a>
                <a href="#" class="text-gray-500 hover:text-black duration-300">Log In</a>
                <a href="#" class="text-gray-500 hover:text-black duration-300">Sign Up</a>
            </nav>
        </div>
    </header>
</template>
  
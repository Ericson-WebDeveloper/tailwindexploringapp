<template>
    <div id="search-input" class="bg-gray-100">
        <form class="w-full">
            <div class="flex flex-wrap justify-center -mx-3 mb-6 p-10 text-center">
                <div class="flex items-center w-full md:w-1/4 px-3 mb-6 md:mb-0">
                    <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-search'></i>
                    <input class="-mx-6 px-8 appearance-none block w-full bg-gray-200 text-gray-700 border rounded py-3
                    leading-tight focus:outline-none focus:bg-white " id="grid-first-name" type="text" placeholder="Job, Keyword or Company">
                    <p class="text-red-500 text-xs italic"></p>
                </div>
                <div class="flex items-center w-full md:w-1/4 px-3 mb-6 md:mb-0">
                    <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-map-marker-alt'></i>
                    <input class="-mx-6 px-8 appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 
                    leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Area, City or Town">
                </div>
                <div class="flex items-center w-full md:w-1/4 px-3">
                    <i class='ml-3 items-centerfill-current text-gray-400 text-xs z-10 fas fa-user-md'></i>
                    <input class="-mx-6 px-8 appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3
                    leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Specialization">
                </div>
                <div class="w-full md:w-24 px-2">
                   <a href="#" class="inline-block text-sm leading-none border rounded text-white bg-green-500 border-green-400 
                    hover:border-transparent hover:text-white hover:bg-green-300 lg:mt-0 py-4 px-4 mt-4 md:mt-0">Search</a>
                </div>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    setup() {

    }
}
</script>
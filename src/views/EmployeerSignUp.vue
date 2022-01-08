<template>
    <div class="w-full h-screen flex items-center justify-center bg-gray-200">
        <form class="w-full mx-5 md:w-2/5 lg:w-1/3 bg-white rounded-lg">
            <h1 class="text-4xl text-center text-gray-700 mb-4 mt-3">Start Hiring with Us!</h1>
            <h3 class="text-1xl text-center text-gray-700 mb-2 mt-2">
             <i class='text-gray-400 text-xs  fas fa-check'></i> 1st choice among Filipino job seekers*
             </h3>
             <h3 class="text-1xl text-center text-gray-700 mb-2 mt-2">
             <i class='text-gray-400 text-xs  fas fa-check'></i> Access more than 12 million talents in the Philippines*
             </h3>
             <h3 class="text-1xl text-center text-gray-700 mb-2 mt-2">
             <i class='text-gray-400 text-xs  fas fa-check'></i> Most searched for career partner*
             </h3>
            <div class="flex font-bold justify-center mt-6">
                <img class="h-20 w-20"
                    src="https://raw.githubusercontent.com/sefyudem/Responsive-Login-Form/master/img/avatar.svg">
            </div>
            <h2 class="text-3xl text-center text-gray-700 mb-4">Employeer Register Form</h2>

            <div class="px-12 pb-10">

                <div class="w-full mb-2">
                    <div class="flex items-center">
                        <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-building'></i>
                        <input type='text' placeholder="Register Bussiness Name"
                            class="-mx-6 px-8  w-full border rounded py-2 text-gray-700 focus:outline-none focus:border-green-500" />
                    </div>
                </div>

                <div class="w-full mb-2">
                    <div class="flex items-center">
                        <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-user'></i>
                        <input type='text' placeholder="Full Name"
                            class="-mx-6 px-8  w-full border rounded py-2 text-gray-700 focus:outline-none focus:border-green-500" />
                    </div>
                </div>
                <div class="w-full mb-2">
                    <div class="flex items-center">
                        <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-envelope'></i>
                        <input type='email' placeholder="Email"
                            class="-mx-6 px-8  w-full border rounded py-2 text-gray-700 focus:outline-none focus:border-green-500" />
                    </div>
                </div>
        
                <div class="w-full mb-2">
                    <div class="flex items-center">
                        <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-lock'></i>
                        <input type='text' placeholder="Password"
                            class="-mx-6 px-8 w-full border rounded py-2 text-gray-700 focus:outline-none focus:border-green-500" />
                    </div>
                </div>
                <div class="w-full mb-2">
                    <div class="flex items-center">
                        <i class='ml-3 fill-current text-gray-400 text-xs z-10 fas fa-lock'></i>
                        <input type='text' placeholder="Password Confirmation"
                            class="-mx-6 px-8 w-full border rounded py-2 text-gray-700 focus:outline-none focus:border-green-500" />
                    </div>
                </div>
                <button type="button"
                    class="w-full py-2 rounded-full bg-green-600 text-gray-100 focus:outline-none hover:bg-green-500">Register Company</button>
                    <router-link :to="{ name: 'Login' }" class="text-sm text-green-500 float-right mb-4 mt-2">Already Have Account?</router-link>
            </div>
        </form>
    </div>
</template>
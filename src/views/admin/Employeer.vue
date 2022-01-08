<template>
    <div id="home" class="flex">
        <div class="main-content flex-1 bg-gray-100 pb-24 md:pb-5">

            <div class="bg-gray-800">
                <div class=" bg-blue-900 p-4 shadow text-2xl text-white">
                    <h3 class="font-bold pl-2">Employeers</h3>
                </div>
            </div>

           <!-- This example requires Tailwind CSS v2.0+ https://tailwindui.com/components/application-ui/lists/tables -->
            <div class="min-h-screen">
                <div class=" p-5"> 
                    <div class="-my-2 overflow-x-auto lg:overflow-x-hidden sm:-mx-6 lg:-mx-8">
                        <div class="py-2 align-middle inline-block min-w-full sm:px-6 lg:px-8">
                            <div class="shadow overflow-hidden border-b border-gray-200 sm:rounded-lg">
                                <table class="min-w-full divide-y divide-gray-200">
                                    <thead class="bg-gray-50">
                                        <tr>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                                            Person
                                        </th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                                            Company
                                        </th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                                            Subcription
                                        </th>
                                        <th scope="col" class="relative px-6 py-3">
                                            <span class="sr-only">Action</span>
                                        </th>
                                        </tr>
                                    </thead>
                                    <tbody class="bg-white divide-y divide-gray-200">
                                        <tr>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="flex items-center">
                                                <div class="flex-shrink-0 h-10 w-10">
                                                    <img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60" alt="">
                                                </div>
                                                <div class="ml-4">
                                                    <div class="text-sm font-medium text-gray-900">
                                                    Jane Cooper
                                                    </div>
                                                    <div class="text-sm text-gray-500">
                                                    jane.cooper@example.com
                                                    </div>
                                                </div>
                                                </div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="text-sm text-gray-900">Name</div>
                                                <div class="text-sm text-gray-500">Industry</div>
                                            </td>

                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                                User
                                                </span>
                                            </td>
                                     
                                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium space-x-2">
                                                <a href="javascript:void(0);" @click.prevent="viewEmployeer(1)" class="bg-green-600 p-2 rounded 
                                                text-green-200 hover:text-green-900">View</a>
                                                <a href="javascript:void(0);" @click.prevent="updateAccount('activate')" class="bg-blue-600 p-2 rounded 
                                                text-blue-200 hover:text-blue-900">Activate</a>
                                                <a href="javascript:void(0);" @click.prevent="updateAccount('deactivate')" class="bg-red-600 p-2 rounded 
                                                text-blue-200 hover:text-red-900">DeActivate</a>
                                            </td>
                                        </tr>

                                        <tr>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="flex items-center">
                                                <div class="flex-shrink-0 h-10 w-10">
                                                    <img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60" alt="">
                                                </div>
                                                <div class="ml-4">
                                                    <div class="text-sm font-medium text-gray-900">
                                                    Jane Cooper
                                                    </div>
                                                    <div class="text-sm text-gray-500">
                                                    jane.cooper@example.com
                                                    </div>
                                                </div>
                                                </div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="text-sm text-gray-900">Name</div>
                                                <div class="text-sm text-gray-500">Industry</div>
                                            </td>
   
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                                Employeer
                                                </span>
                                            </td>
                                     
                                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium space-x-2">
                                                <a href="javascript:void(0);" @click.prevent="viewEmployeer(1)" class="bg-green-600 p-2 rounded 
                                                text-green-200 hover:text-green-900">View</a>
                                                <a href="javascript:void(0);" @click.prevent="updateAccount('activate')" class="bg-blue-600 p-2 rounded 
                                                text-blue-200 hover:text-blue-900">Activate</a>
                                                <a href="javascript:void(0);" @click.prevent="updateAccount('deactivate')" class="bg-red-600 p-2 rounded 
                                                text-blue-200 hover:text-red-900">DeActivate</a>
                                            </td>
                                        </tr>

                                        <tr>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="flex items-center">
                                                <div class="flex-shrink-0 h-10 w-10">
                                                    <img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=4&w=256&h=256&q=60" alt="">
                                                </div>
                                                <div class="ml-4">
                                                    <div class="text-sm font-medium text-gray-900">
                                                    Jane Cooper
                                                    </div>
                                                    <div class="text-sm text-gray-500">
                                                    jane.cooper@example.com
                                                    </div>
                                                </div>
                                                </div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="text-sm text-gray-900">Name</div>
                                                <div class="text-sm text-gray-500">Industry</div>
                                            </td>

                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                                User
                                                </span>
                                            </td>
                                     
                                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium space-x-2">
                                                <a href="javascript:void(0);" @click.prevent="viewEmployeer(1)" class="bg-green-600 p-2 rounded 
                                                text-green-200 hover:text-green-900">View</a>
                                                <a href="javascript:void(0);" @click.prevent="updateAccount('activate')" class="bg-blue-600 p-2 rounded 
                                                text-blue-200 hover:text-blue-900">Activate</a>
                                                <a href="javascript:void(0);" @click.prevent="updateAccount('deactivate')" class="bg-red-600 p-2 rounded 
                                                text-blue-200 hover:text-red-900">DeActivate</a>
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div> 
            </div>

        </div>



            <!-- View Employeer -->
            <div class="h-screen w-full fixed left-0 top-0 flex justify-center items-center bg-black bg-opacity-50 overflow-y-auto" :class="[employeerView ? '' : 'hidden']">
                <div class="bg-white rounded shadow-lg w-4/5 lg:w-2/5 my-auto">
                    <div class="flex justify-between border-b px-4 py-2 ">
                        <h1 class="text-2xl font-bold font-serif">Employeer Profile</h1>
                        <svg @click="employeerView = !employeerView" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-600 cursor-pointer hover:bg-gray-100" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </div>

                <div class="p-3 ">
                    <div class="mx-auto">
                        <div class="">
                    
                            <div class="mt-2 bg-white rounded-lg shadow">
                                <div class="flex">
                                    <div class="flex-1 py-5 pl-5 overflow-hidden">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="21" height="20.5" class="inline align-text-top" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                                        </svg>
                                        <h1 class="inline text-2xl font-semibold leading-none ml-2">Profile</h1>
                                    </div>
                                </div>
                                <div class="px-5 pb-5">
                                    <img src="../../../public/images/download.png" class="mx-auto w-64 h-64" alt="">
                                    <input  placeholder="Name" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                    <!-- <input  placeholder="Address" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">  -->
                                    <div class="flex flex-col md:flex-row">
                                        <div class="w-full md:flex-grow md:w-2/4 md:pr-2">
                                            <input  placeholder="Email" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                        <div class="w-full md:flex-grow md:w-2/4">
                                            <input placeholder="age" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                    </div>

                                    <div class="flex flex-col md:flex-row">
                                        <div class="w-full md:flex-grow md:w-2/4 md:pr-2">
                                            <input  placeholder="Course" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                        <div class="w-full md:flex-grow md:w-2/4">
                                            <input placeholder="College" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                    </div>
                                    <input  placeholder="Job" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                    focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                    <button @click.prevent="viewProfile(1)" class="bg-blue-500 p-2 rounded  w-full px-4 py-2.5 mt-2 text-white hover:bg-blue-600">View Full Information</button>
                                </div>
                            </div>

                            <div class="mt-2 bg-white rounded-lg shadow">
                                <div class="flex">
                                    <div class="flex-1 py-5 pl-5 overflow-hidden">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="21" height="20.5" class="inline align-text-top" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                                        </svg>
                                        <h1 class="inline text-2xl font-semibold leading-none ml-2">Company</h1>
                                    </div>
                                </div>
                                <div class="px-5 pb-5">
                                     <img src="../../../public/images/download.png" class="mx-auto w-64 h-64" alt="">
                                    <input  placeholder="Company Name" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                    <input  placeholder="Address" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400">

                                    <input  placeholder="Industry" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400">
                                    <textarea name="company_overview" id="company_overview" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>

                                    <textarea name="additional_info" id="additional_info" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>
                                </div>
                            </div>
                          
                        </div>
                    </div>
                </div>

                <div class="flex justify-end items-center w-100 border-t p-3 space-x-5">
                    <button class="bg-red-500 p-2 rounded text-white hover:bg-red-600" @click="employeerView = !employeerView">Cancel</button>
                    <!-- <button class="bg-blue-500 p-2 rounded text-white hover:bg-blue-600">Submit</button> -->
                </div>
             </div>
           </div>


           <!-- View Employeer -->
            <div class="h-screen w-full fixed left-0 top-0 flex justify-center items-center bg-black bg-opacity-50 overflow-y-auto" 
            :class="[activateView ? '' : 'hidden']">
                <div class="bg-white rounded shadow-lg w-4/5 lg:w-2/5 my-auto">
                    <div class="flex justify-between border-b px-4 py-2 ">
                        <h1 class="text-2xl font-bold font-serif">Activate/Deactivate Employeer Account</h1>
                        <svg @click="activateView = !activateView" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-600 cursor-pointer hover:bg-gray-100" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </div>

                    <div class="p-3 ">
                        <div class="mx-auto">
                            <div class="">
                                <div class="mt-2 bg-white rounded-lg shadow">
                                    <div class="flex">
                                        <div class="flex-1 py-5 pl-5 text-center overflow-hidden">
                                            <!-- <svg xmlns="http://www.w3.org/2000/svg" width="21" height="20.5" class="inline align-text-top" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                                            </svg> -->
                                            <svg xmlns="http://www.w3.org/2000/svg" width="21" height="20.5" class="inline align-text-top" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                                            </svg>
                                            <h1 class="inline text-2xl font-semibold leading-none ml-2">
                                                are you sure to activate/deactivate this account?</h1>
                                        </div>
                                    </div>
                                    <!-- <div class="px-5 pb-5">
                                        <label for="">are you sure?</label>
                                    </div> -->
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="flex justify-end items-center w-100 border-t p-3 space-x-5">
                        <button class="bg-red-500 p-2 rounded text-white hover:bg-red-600" @click="activateView = !activateView">Cancel</button>
                        <button class="bg-blue-500 p-2 rounded text-white hover:bg-blue-600">Submit</button>
                    </div>
                </div>
           </div>




    </div>
</template>

<script>
import {ref, onMounted} from 'vue';
import {useRouter} from 'vue-router';
export default {
  setup() {
        const employeerView = ref(false);
        const activateView = ref(false);
        const router = useRouter();

    onMounted(() => {
    
    });

    const updateAccount = (type) => {
        console.log(type)
        activateView.value = !activateView.value
    }

    const viewEmployeer = (id) => {
        console.log(id);
        employeerView.value = !employeerView.value
    }

    const viewProfile = (userid) => {
        router.push({name: 'User-View', params: {userid}});
        // with query, resulting in /register?plan=private
        // router.push({ path: 'register', query: { plan: 'private' } })
    }
    return { 
      employeerView, viewEmployeer, activateView, updateAccount, viewProfile
    }
  }
}
</script>
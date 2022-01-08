<template>
    <div id="home" class="flex">
        <div class="main-content flex-1 bg-gray-100 pb-24 md:pb-5">

            <div class="bg-gray-800">
                <div class=" bg-blue-900 p-4 shadow text-2xl text-white">
                    <h3 class="font-bold pl-2">Jobs List</h3>
                </div>
            </div>
            <a href="javascript:void(0);" @click.prevent="AddJob()"
            class="bg-green-600 p-2 rounded text-green-200 hover:text-green-900 ml-3 mt-5">
            Add New Job</a>

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
                                            Title
                                        </th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                                            Position
                                        </th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                                            specialization
                                        </th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">
                                            Status
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
                                                <div class="text-sm text-gray-900">Regional Paradigm Technician</div>
                                                <div class="text-sm text-gray-500">Optimization</div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="text-sm text-gray-900">BSHR</div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                                User
                                                </span>
                                            </td>
                                     
                                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium space-x-2">
                                                <a href="javascript:void(0);" @click="Viewjob(1)" class="bg-green-600 p-2 rounded text-green-200 hover:text-green-900">View</a>
                                                <a href="javascript:void(0);" @click="Updatejob(1)" class="bg-yellow-600 p-2 rounded text-yellow-200 
                                                hover:text-yellow-900">Update</a>

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
                                                <div class="text-sm text-gray-900">Regional Paradigm Technician</div>
                                                <div class="text-sm text-gray-500">Optimization</div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="text-sm text-gray-900">BSCS</div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                                Employeer
                                                </span>
                                            </td>
                                     
                                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium space-x-2">
                                                <a href="javascript:void(0);" @click="Viewjob(1)" class="bg-green-600 p-2 rounded text-green-200 hover:text-green-900">View</a>
                                            <a href="javascript:void(0);" @click="Updatejob(1)" class="bg-yellow-600 p-2 rounded text-yellow-200 
                                                hover:text-yellow-900">Update</a>
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
                                                <div class="text-sm text-gray-900">Regional Paradigm Technician</div>
                                                <div class="text-sm text-gray-500">Optimization</div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <div class="text-sm text-gray-900">BSIT</div>
                                            </td>
                                            <td class="px-6 py-4 whitespace-nowrap">
                                                <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">
                                                User
                                                </span>
                                            </td>
                                     
                                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium space-x-2">
                                                <a href="javascript:void(0);" @click="Viewjob(1)" class="bg-green-600 p-2 rounded text-green-200 hover:text-green-900">View</a>
                                                <a href="javascript:void(0);" @click="Updatejob(1)" class="bg-yellow-600 p-2 rounded text-yellow-200 
                                                hover:text-yellow-900">Update</a>
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



        <!-- View Job -->
            <div class="h-screen w-full fixed left-0 top-0 flex justify-center items-center bg-black bg-opacity-50 overflow-y-auto" 
            :class="[jobView ? '' : 'hidden']">
                <div class="bg-white rounded shadow-lg w-4/5 lg:w-2/5 my-auto">
                    <div class="flex justify-between border-b px-4 py-2 ">
                        <h1 class="text-2xl font-bold font-serif">Job details</h1>
                        <svg @click="jobView = !jobView" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-600 cursor-pointer hover:bg-gray-100" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </div>

                <div class="p-3 ">
                    <div class="mx-auto">
                        <div class="">
                    
                            <div class="mt-2 bg-white rounded-lg shadow">
                        
                                <div class="px-5 pb-5">
                                    <label for="email" class="block text-xl font-semibold text-gray-600">Title</label>
                                    <input  placeholder="Title" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                    <!-- <input  placeholder="Address" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">  -->
                                    <div class="flex flex-col md:flex-row">
                                        <div class="w-full md:flex-grow md:w-2/4 md:pr-2">
                                        <label for="email" class="block text-xl font-semibold text-gray-600">Position</label>
                                            <input  placeholder="Position" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base  
                                             transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                             focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline 
                                             focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                        <div class="w-full md:flex-grow md:w-2/4">
                                            <label for="email" class="block text-xl font-semibold text-gray-600">Specialization</label>
                                            <input placeholder="specialization" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                            transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                            focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline 
                                            focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                    </div>
                                     <div class="flex flex-col my-2">
                                         <div class="block">
                                             <label for="email" class="block text-xl font-semibold text-gray-600">Status</label>
                                            <div class="mt-2">
                                                <div>
                                                    <label class="inline-flex items-center">
                                                        <input
                                                    type="radio"
                                                    class="form-radio"
                                                    name="radio"
                                                    value="1"
                                                    checked
                                                    />
                                                        <span class="ml-2">Close</span>
                                                    </label>
                                                </div>
                                                <div>
                                                    <label class="inline-flex items-center">
                                                        <input type="radio" class="form-radio" name="radio" value="2" />
                                                        <span class="ml-2">Open</span>
                                                    </label>
                                                </div>
                                            </div>
                                        </div>   
                                    </div>
                                    
            
                                    <label for="Salary" class="block text-xl font-semibold text-gray-600">Salary</label>
                                    <input  placeholder="Salary" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                    focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">

                                     <label for="job_details" class="block text-xl font-semibold text-gray-600">Job Details</label>
                                    <textarea name="job_details" id="job_details" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>

                                    <label for="additional_details" class="block text-xl font-semibold text-gray-600">Additional Details</label>
                                    <textarea name="additional_details" id="additional_details" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>
                                
                                </div>
                            </div>

                     
                          
                        </div>
                    </div>
                </div>

                <div class="flex justify-end items-center w-100 border-t p-3 space-x-5">
                    <button class="bg-red-500 p-2 rounded text-white hover:bg-red-600" @click="jobView = !jobView">Close</button>
                    <!-- <button class="bg-blue-500 p-2 rounded text-white hover:bg-blue-600">Submit</button> -->
                </div>
             </div>
           </div>


        <!-- Add New Job -->
            <div class="h-screen w-full fixed left-0 top-0 flex justify-center items-center bg-black bg-opacity-50 overflow-y-auto" 
            :class="[jobAdd ? '' : 'hidden']">
                <div class="bg-white rounded shadow-lg w-4/5 lg:w-2/5 my-auto">
                    <div class="flex justify-between border-b px-4 py-2 ">
                        <h1 class="text-2xl font-bold font-serif">Add New Job</h1>
                        <svg @click="jobAdd = !jobAdd" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-600 cursor-pointer hover:bg-gray-100" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </div>

                <div class="p-3 ">
                    <div class="mx-auto">
                        <div class="">
                    
                            <div class="mt-2 bg-white rounded-lg shadow">
                        
                                <div class="px-5 pb-5">
                                    <label for="email" class="block text-xl font-semibold text-gray-600">Title</label>
                                    <input  placeholder="Title" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                    <!-- <input  placeholder="Address" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">  -->
                                    <div class="flex flex-col md:flex-row">
                                        <div class="w-full md:flex-grow md:w-2/4 md:pr-2">
                                        <label for="email" class="block text-xl font-semibold text-gray-600">Position</label>
                                            <input  placeholder="Position" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base  
                                             transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                             focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline 
                                             focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                        <div class="w-full md:flex-grow md:w-2/4">
                                            <label for="email" class="block text-xl font-semibold text-gray-600">Specialization</label>
                                            <input placeholder="specialization" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                            transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                            focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline 
                                            focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                    </div>
                                     <div class="flex flex-col my-2">
                                         <div class="block">
                                             <label for="email" class="block text-xl font-semibold text-gray-600">Status</label>
                                            <div class="mt-2">
                                                <div>
                                                    <label class="inline-flex items-center">
                                                        <input
                                                    type="radio"
                                                    class="form-radio"
                                                    name="radio"
                                                    value="1"
                                                    checked
                                                    />
                                                        <span class="ml-2">Close</span>
                                                    </label>
                                                </div>
                                                <div>
                                                    <label class="inline-flex items-center">
                                                        <input type="radio" class="form-radio" name="radio" value="2" />
                                                        <span class="ml-2">Open</span>
                                                    </label>
                                                </div>
                                            </div>
                                        </div>   
                                    </div>
                                    
            
                                    <label for="Salary" class="block text-xl font-semibold text-gray-600">Salary</label>
                                    <input  placeholder="Salary" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                    focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">

                                     <label for="job_details" class="block text-xl font-semibold text-gray-600">Job Details</label>
                                    <textarea name="job_details" id="job_details" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>

                                    <label for="additional_details" class="block text-xl font-semibold text-gray-600">Additional Details</label>
                                    <textarea name="additional_details" id="additional_details" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>
                                
                                </div>
                            </div>

                     
                          
                        </div>
                    </div>
                </div>

                <div class="flex justify-end items-center w-100 border-t p-3 space-x-5">
                    <button class="bg-red-500 p-2 rounded text-white hover:bg-red-600" @click="jobAdd = !jobAdd">Close</button>
                    <button class="bg-blue-500 p-2 rounded text-white hover:bg-blue-600">Submit</button>
                </div>
             </div>
           </div>


           <!-- Edit Job -->
            <div class="h-screen w-full fixed left-0 top-0 flex justify-center items-center bg-black bg-opacity-50 overflow-y-auto" 
            :class="[jobEdit ? '' : 'hidden']">
                <div class="bg-white rounded shadow-lg w-4/5 lg:w-2/5 my-auto">
                    <div class="flex justify-between border-b px-4 py-2 ">
                        <h1 class="text-2xl font-bold font-serif">Edit Job</h1>
                        <svg @click="jobEdit = !jobEdit" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-red-600 cursor-pointer hover:bg-gray-100" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </div>

                <div class="p-3 ">
                    <div class="mx-auto">
                        <div class="">
                    
                            <div class="mt-2 bg-white rounded-lg shadow">
                        
                                <div class="px-5 pb-5">
                                    <label for="email" class="block text-xl font-semibold text-gray-600">Title</label>
                                    <input  placeholder="Title" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                    <!-- <input  placeholder="Address" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">  -->
                                    <div class="flex flex-col md:flex-row">
                                        <div class="w-full md:flex-grow md:w-2/4 md:pr-2">
                                        <label for="email" class="block text-xl font-semibold text-gray-600">Position</label>
                                            <input  placeholder="Position" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base  
                                             transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                             focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline 
                                             focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                        <div class="w-full md:flex-grow md:w-2/4">
                                            <label for="email" class="block text-xl font-semibold text-gray-600">Specialization</label>
                                            <input placeholder="specialization" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                            transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                            focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline 
                                            focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">
                                        </div>
                                    </div>
                                     <div class="flex flex-col my-2">
                                         <div class="block">
                                             <label for="email" class="block text-xl font-semibold text-gray-600">Status</label>
                                            <div class="mt-2">
                                                <div>
                                                    <label class="inline-flex items-center">
                                                        <input
                                                    type="radio"
                                                    class="form-radio"
                                                    name="radio"
                                                    value="1"
                                                    checked
                                                    />
                                                        <span class="ml-2">Close</span>
                                                    </label>
                                                </div>
                                                <div>
                                                    <label class="inline-flex items-center">
                                                        <input type="radio" class="form-radio" name="radio" value="2" />
                                                        <span class="ml-2">Open</span>
                                                    </label>
                                                </div>
                                            </div>
                                        </div>   
                                    </div>
                                    
            
                                    <label for="Salary" class="block text-xl font-semibold text-gray-600">Salary</label>
                                    <input  placeholder="Salary" class=" text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base   
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  
                                    focus:border-blueGray-500 focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current ring-offset-2 ring-gray-400">

                                     <label for="job_details" class="block text-xl font-semibold text-gray-600">Job Details</label>
                                    <textarea name="job_details" id="job_details" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>

                                    <label for="additional_details" class="block text-xl font-semibold text-gray-600">Additional Details</label>
                                    <textarea name="additional_details" id="additional_details" class="text-black placeholder-gray-600 w-full px-4 py-2.5 mt-2 text-base 
                                    transition duration-500 ease-in-out transform border-transparent rounded-lg bg-gray-200  focus:border-blueGray-500 
                                    focus:bg-white dark:focus:bg-gray-800 focus:outline-none focus:shadow-outline focus:ring-2 ring-offset-current 
                                    ring-offset-2 ring-gray-400" cols="30" rows="10"></textarea>
                                
                                </div>
                            </div>

                     
                          
                        </div>
                    </div>
                </div>

                <div class="flex justify-end items-center w-100 border-t p-3 space-x-5">
                    <button class="bg-red-500 p-2 rounded text-white hover:bg-red-600" @click="jobEdit = !jobEdit">Close</button>
                    <button class="bg-blue-500 p-2 rounded text-white hover:bg-blue-600">Submit</button>
                </div>
             </div>
           </div>

    </div>
</template>

<script>
import {ref, onMounted} from 'vue'
export default {
  setup() {
    const jobView = ref(false);
    const jobAdd = ref(false);
    const jobEdit = ref(false);

    onMounted(() => {
    
    });

    const Viewjob = (id) => {
        console.log(id)
        jobView.value = !jobView.value
    }

    const AddJob = () => {
        jobAdd.value = !jobAdd.value
    }

    const Updatejob = (id) => {
        console.log(id)
        jobEdit.value = !jobEdit.value
    }

    return { 
        jobView, Viewjob, jobAdd, AddJob, jobEdit, Updatejob
    }
  }
}
</script>
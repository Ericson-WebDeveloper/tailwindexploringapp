<template>
  <div class="home">
    <search-input></search-input>
    <div class="container mx-auto">
      <div class="content">
          <div id="job-content-list">
          <p class="mb-2 ml-12">1/123</p>
            <div class="flex lg:flex-row gap-4 h-screen"> <!-- flex-col -->
              
              <div class="w-full lg:w-2/5 items-center overflow-y-auto">
                <div class="flex flex-col"> <!-- max-h-full -->
                  <div class="mb-2">
                    <div class="max-w-auto mx-4 rounded overflow-hidden shadow-lg p-2 border-l-8 border-green-800">
                      <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                      <div class="px-6 py-4">
                        <div class="mb-2">
                          <router-link :to="{name:'Companies'}" class="font-bold text-xl text-blue-500">AWS</router-link> <br>
                          <router-link :to="{name:'Companies'}" class="">
                            <p class="font-bold hover:underline">The Coldest Sunset</p>
                          </router-link> 
                          <!-- link to show job Details -->
                        </div>
                        <p class="text-gray-700 text-base">
                          Central Visayas,
                        </p>
                        <p class="text-gray-700 text-base">
                          PHP 70K - 120K monthly
                        </p>
                        <br><br>
                        <p class="text-gray-700 text-base">
                          2 days ago
                        </p>
                      </div>
                      <div class="px-6 pt-4 pb-2">
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                      </div>
                    </div>
                  </div>

                <div class="mb-2 border-2">
                  <div class="max-w-lg rounded overflow-hidden shadow-lg">
                    <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                    <div class="px-6 py-4">
                      <div class="font-bold text-xl mb-2">
                        <router-link :to="{name:'Companies'}" class="text-blue-500">The Coldest Sunset</router-link>
                      </div>
                      <p class="text-gray-700 text-base">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
                      </p>
                    </div>
                    <div class="px-6 pt-4 pb-2">
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                    </div>
                  </div>
                </div>

                <div class="mb-2 border-2">
                  <div class="max-w-lg rounded overflow-hidden shadow-lg">
                    <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                    <div class="px-6 py-4">
                      <div class="font-bold text-xl mb-2">
                        <router-link :to="{name:'Companies'}" class="text-blue-500">The Coldest Sunset</router-link>
                      </div>
                      <p class="text-gray-700 text-base">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
                      </p>
                    </div>
                    <div class="px-6 pt-4 pb-2">
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                    </div>
                  </div>
                </div>

                <div class="mb-2 border-2">
                  <div class="max-w-lg rounded overflow-hidden shadow-lg">
                    <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                    <div class="px-6 py-4">
                      <div class="font-bold text-xl mb-2">
                        <router-link :to="{name:'Companies'}" class="text-blue-500">The Coldest Sunset</router-link>
                      </div>
                      <p class="text-gray-700 text-base">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
                      </p>
                    </div>
                    <div class="px-6 pt-4 pb-2">
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                    </div>
                  </div>
                </div>

                <div class="mb-2 border-2">
                  <div class="max-w-lg rounded overflow-hidden shadow-lg">
                    <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                    <div class="px-6 py-4">
                      <div class="font-bold text-xl mb-2">
                        <router-link :to="{name:'Companies'}" class="text-blue-500">The Coldest Sunset</router-link>
                      </div>
                      <p class="text-gray-700 text-base">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
                      </p>
                    </div>
                    <div class="px-6 pt-4 pb-2">
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                    </div>
                  </div>
                </div>

                <div class="mb-2 border-2">
                  <div class="max-w-lg rounded overflow-hidden shadow-lg">
                    <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                    <div class="px-6 py-4">
                      <div class="font-bold text-xl mb-2">
                        <router-link :to="{name:'Companies'}" class="text-blue-500">The Coldest Sunset</router-link>
                      </div>
                      <p class="text-gray-700 text-base">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
                      </p>
                    </div>
                    <div class="px-6 pt-4 pb-2">
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                    </div>
                  </div>
                </div>

                <div class="mb-2 border-2">
                  <div class="max-w-lg rounded overflow-hidden shadow-lg">
                    <img class="w-48" src="../../public/images/download.png" alt="Sunset in the mountains">
                    <div class="px-6 py-4">
                      <div class="font-bold text-xl mb-2">
                        <router-link :to="{name:'Companies'}" class="text-blue-500">The Coldest Sunset</router-link>
                        </div>
                      <p class="text-gray-700 text-base">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
                      </p>
                    </div>
                    <div class="px-6 pt-4 pb-2">
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                      <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                    </div>
                  </div>
                </div>

                <div class="flex justify-center space-x-1 mt-5 mb-10">
                    <a href="#" class="flex items-center px-4 py-2 text-gray-500 bg-gray-300 rounded-md">
                        Previous
                    </a>

                    <a href="#" class="px-4 py-2 text-gray-700 bg-gray-200 rounded-md hover:bg-blue-400 hover:text-white">
                        1
                    </a>
                    <a href="#" class="px-4 py-2 text-gray-700 bg-gray-200 rounded-md hover:bg-blue-400 hover:text-white">
                        2
                    </a>
                    <a href="#" class="px-4 py-2 text-gray-700 bg-gray-200 rounded-md hover:bg-blue-400 hover:text-white">
                        3
                    </a>
                    <a href="#" class="px-4 py-2 font-bold text-gray-500 bg-gray-300 rounded-md hover:bg-blue-400 hover:text-white">
                        Next
                    </a>
                </div>

                </div>
              </div>
              <div class=" lg:block lg:w-3/5 bg-gray-100 hidden overflow-y-auto"> <!-- flex flex-col -->
                <div class="content p-12">
                  <h1>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?</h1>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?

                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?

                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt? 
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed perspiciatis cupiditate nisi sequi tempore 
                    reprehenderit voluptas non, ipsam iure id praesentium, explicabo ad! Aut est similique sit atque, aperiam deserunt?
                    
                </div>
              </div>

            </div>
          </div>

      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import SearchInput from '@/components/SearchInput'

export default {
  name: 'Home',
  components: {
    SearchInput
  }
}
</script>

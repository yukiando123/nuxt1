<template>
  <div>
<div class="bg-white py-6 sm:py-8 lg:py-12">
  <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
    <!-- text - start -->
    <div class="mb-10 md:mb-16">
      <h2 class="text-gray-800 text-2xl lg:text-3xl font-bold text-center mb-4 md:mb-6">Core Value</h2>

      <p class="max-w-screen-md text-gray-500 md:text-lg text-center mx-auto">This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated.</p>
    </div>
    <!-- text - end -->

    <div class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-x-4 md:gap-x-6 gap-y-8">
    <!-- product - start -->
    <div>
        <nuxt-link to="/page/hanto" class="group h-96 block bg-gray-100 rounded-lg overflow-hidden shadow-lg relative mb-2 lg:mb-3">
            <img src="~/assets/projects/hanto-thum.jpg" loading="lazy" alt="Photo by Austin Wade" class="w-full h-full object-center group-hover:scale-110 transition duration-200" />
        </nuxt-link>

        <div class="gap-2 px-2">
            <div class="flex flex-col">
            <a href="#" class="text-gray-800 hover:text-gray-500 text-lg lg:text-xl font-bold transition duration-100">Hanto Web Media</a>
            <span class="text-gray-500">光文社</span>
        </div>

        </div>
    </div>
    <!-- product - end -->

        <!-- product - start -->
    <div>
        <a href="#" class="group h-96 block bg-gray-100 rounded-lg overflow-hidden shadow-lg relative mb-2 lg:mb-3">
            <img src="~/assets/projects/hanto-new-thum.jpg" loading="lazy" alt="Photo by Austin Wade" class="w-full h-full group-hover:scale-110 transition duration-200" />
        </a>

        <div class="gap-2 px-2">
            <div class="flex flex-col">
            <a href="#" class="text-gray-800 hover:text-gray-500 text-lg lg:text-xl font-bold transition duration-100">SPA Web Site</a>
            <span class="text-gray-500">Atlantic Design</span>
        </div>

        </div>
    </div>
    <!-- product - end -->


        <!-- product - start -->
    <div>
        <a href="#" class="group h-96 block bg-gray-100 rounded-lg overflow-hidden shadow-lg relative mb-2 lg:mb-3">
            <img src="https://images.unsplash.com/photo-1552374196-1ab2a1c593e8?auto=format&q=75&fit=crop&crop=top&w=600&h=700" loading="lazy" alt="Photo by Austin Wade" class="w-full h-full object-cover object-center group-hover:scale-110 transition duration-200" />
        </a>

        <div class="gap-2 px-2">
            <div class="flex flex-col">
            <a href="#" class="text-gray-800 hover:text-gray-500 text-lg lg:text-xl font-bold transition duration-100">Summer Pockets特設サイト</a>
            <span class="text-gray-500">凸版印刷, 小学館集英社プロダクツ, 高松市観光協会</span>
        </div>

        </div>
    </div>
    <!-- product - end -->


        <!-- product - start -->
    <div>
        <a href="#" class="group h-96 block bg-gray-100 rounded-lg overflow-hidden shadow-lg relative mb-2 lg:mb-3">
            <img src="https://images.unsplash.com/photo-1552374196-1ab2a1c593e8?auto=format&q=75&fit=crop&crop=top&w=600&h=700" loading="lazy" alt="Photo by Austin Wade" class="w-full h-full object-cover object-center group-hover:scale-110 transition duration-200" />
        </a>

        <div class="gap-2 px-2">
            <div class="flex flex-col">
            <a href="#" class="text-gray-800 hover:text-gray-500 text-lg lg:text-xl font-bold transition duration-100">横浜市中学校給食</a>
            <span class="text-gray-500">横浜市養育委員会</span>
        </div>

        </div>
    </div>
    <!-- product - end -->


        <!-- product - start -->
    <div>
        <a href="#" class="group h-96 block bg-gray-100 rounded-lg overflow-hidden shadow-lg relative mb-2 lg:mb-3">
            <img src="https://images.unsplash.com/photo-1552374196-1ab2a1c593e8?auto=format&q=75&fit=crop&crop=top&w=600&h=700" loading="lazy" alt="Photo by Austin Wade" class="w-full h-full object-cover object-center group-hover:scale-110 transition duration-200" />
        </a>

        <div class="gap-2 px-2">
            <div class="flex flex-col">
            <a href="#" class="text-gray-800 hover:text-gray-500 text-lg lg:text-xl font-bold transition duration-100">Fancy Outfit</a>
            <span class="text-gray-500">by Fancy Brand</span>
        </div>

        </div>
    </div>
    <!-- product - end -->


        <!-- product - start -->
    <div>
        <a href="#" class="group h-96 block bg-gray-100 rounded-lg overflow-hidden shadow-lg relative mb-2 lg:mb-3">
            <img src="https://images.unsplash.com/photo-1552374196-1ab2a1c593e8?auto=format&q=75&fit=crop&crop=top&w=600&h=700" loading="lazy" alt="Photo by Austin Wade" class="w-full h-full object-cover object-center group-hover:scale-110 transition duration-200" />
        </a>

        <div class="gap-2 px-2">
            <div class="flex flex-col">
            <a href="#" class="text-gray-800 hover:text-gray-500 text-lg lg:text-xl font-bold transition duration-100">Fancy Outfit</a>
            <span class="text-gray-500">by Fancy Brand</span>
        </div>

        </div>
    </div>
    <!-- product - end -->

    </div>
    </div>
</div>
</div>
</template>

<script>
export default {
  layout: 'layout',
  name: 'IndexPage'
}
</script>

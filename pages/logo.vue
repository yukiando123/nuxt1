<template>
<div>
    <div class="bg-white py-6 sm:py-8 lg:py-12">
        <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
    <!-- text - start -->
            <div class="mb-10 md:mb-16">
                <h2 class="text-gray-800 text-2xl lg:text-3xl font-bold text-center mb-4 md:mb-6">Logo Design</h2>
                <!--<p class="max-w-screen-md text-gray-500 md:text-lg text-center mx-auto">This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated.</p>-->
            </div>
    <!-- text - end -->
            <div class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-x-4 md:gap-x-6 gap-y-8">
                <Kurofune />
                <Sakoku />
                <Hdelicious />
                <Hantologo />
                <Newkoenji />
                <Shizuku />
                <Dlepuslogo />
                <Toratshoplogo />
                <Toratlogo />
            </div>
        </div>
    </div>
</div>
</template>

<script>
import Kurofune from '@/components/list/Kurofune.vue';
import Sakoku from '@/components/list/Sakoku.vue';
import Hdelicious from '@/components/list/Hdelicious.vue';
import Hantologo from '@/components/list/Hantologo.vue';
import Newkoenji from '@/components/list/Newkoenji.vue';
import Shizuku from '@/components/list/Shizuku.vue';
import Dlepuslogo from '@/components/list/Dlepuslogo.vue';
import Toratshoplogo from '@/components/list/Toratshoplogo.vue';
import Toratlogo from '@/components/list/Toratlogo.vue';

export default {
    layout: 'layout',
    components:{
        Kurofune,
        Sakoku,
        Hdelicious,
        Hantologo,
        Newkoenji,
        Shizuku,
        Dlepuslogo,
        Toratshoplogo,
        Toratlogo
    }
}
</script>
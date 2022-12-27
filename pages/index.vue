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
    <Kurofune />
    <Sakoku />
    <Hdelicious />
    <Knuts />
    <Yokohamasho />
    <Hanto />
    <Hantologo />
    <Catbokaiin />
    <Ccat />
    <Catbopamph />
    <Kyushoku />
    <Catbopost />
    <Catbo />
    <Newkoenji />
    <Sanlogi />
    <Shizuku />
    <Dlepus />
    <Toratshop />
    <Torat />
    <!--<Summer />-->
    <!--<Yokohama />-->

    </div>
    </div>
</div>
</div>
</template>

<script>
import Hanto from '@/components/list/Hanto.vue';
import HantoNew from '@/components/list/HantoNew.vue';
import Summer from '@/components/list/Summer.vue';
import Catbo from '@/components/list/Catbo.vue';
import Yokohama from '@/components/list/Yokohama.vue';
import Newkoenji from '@/components/list/Newkoenji.vue';
import Torat from '@/components/list/Torat.vue';
import Sakoku from '@/components/list/Sakoku.vue';
import Dlepus from '@/components/list/Dlepus.vue';
import Yokohamasho from '@/components/list/Yokohamasho.vue';
import Ccat from '@/components/list/Ccat.vue';
import Kurofune from '@/components/list/Kurofune.vue';
import Toratshop from '@/components/list/Toratshop.vue';
import Hdelicious from '@/components/list/Hdelicious.vue';
import Shizuku from '@/components/list/Shizuku.vue';
import Kyushoku from '@/components/list/Kyushoku.vue';
import Knuts from '@/components/list/Knuts.vue';
import Sanlogi from '@/components/list/Sanlogi.vue';
import Hantologo from '@/components/list/Hantologo.vue';
import Catbopost from '@/components/list/Catbopost.vue';
import Catbopamph from '@/components/list/Catbopamph.vue';
import Catbokaiin from '@/components/list/Catbokaiin.vue';




export default {
  layout: 'layout',
  name: 'IndexPage',
  components:{
    Hanto,
    HantoNew,
    Summer,
    Catbo,
    Yokohama,
    Newkoenji,
    Torat,
    Sakoku,
    Dlepus,
    Yokohamasho,
    Ccat,
    Kurofune,
    Toratshop,
    Shizuku,
    Hdelicious,
    Kyushoku,
    Knuts,
    Sanlogi,
    Hantologo,
    Catbopost,
    Catbopamph,
    Catbokaiin
  }
}
</script>
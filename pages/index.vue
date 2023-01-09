<template>
  <div>
<div class="bg-white py-6 sm:py-8 lg:py-12">
  <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
    <!-- text - start -->
    <div class="mb-10 md:mb-16">
      <h2 class="text-gray-800 text-2xl lg:text-3xl font-bold text-center mb-4 md:mb-6">Core Value</h2>

      <p class="max-w-screen-lg text-gray-500 md:text-base text-center mx-auto text-base">この世界は、デザインで溢れています。<br>世の中の全てのプロダクトには制作者の想い、誰かの思いやり、優しさが込められたデザインになっていると、日々そんなことをひしひしと感じます。ユーザーの使いやすさ操作性、デジタルを通して得られる体験を考えたUI／UXから、全ての人のためのデザインであるユニバーサルデザイン。世の中はそんな思いやりに満ちたデザインで溢れています。
      <br>わたしは、散文的なデザインではなく、関わる全ての人のためのデザイン<br>皆様の日々をより素敵にするデザインを手掛けたいと思っております。</p>
    </div>
    <!-- text - end -->

    <div class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-x-4 md:gap-x-6 gap-y-8">
    <Kurofune />
    <Sakoku />
    <Hdelicious />
    <Hantonew />
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
    <Newkoenjilogo />
    <Sanlogi />
    <Yokohama />
    <Shizuku />
    <Dlepuslogo />
    <Dlepus />
    <Eastern />
    <Kamikochi />
    <Toratshoplogo />
    <Toratshop />
    <Toratlogo />
    <Torat />
    <!--<Summer />-->

    </div>
    </div>
</div>
</div>
</template>

<script>
import Hanto from '@/components/list/Hanto.vue';
import Hantonew from '@/components/list/Hantonew.vue';
import Summer from '@/components/list/Summer.vue';
import Catbo from '@/components/list/Catbo.vue';
import Yokohama from '@/components/list/Yokohama.vue';
import Newkoenji from '@/components/list/Newkoenji.vue';
import Newkoenjilogo from '@/components/list/Newkoenjilogo.vue';
import Torat from '@/components/list/Torat.vue';
import Toratlogo from '@/components/list/Toratlogo.vue';
import Sakoku from '@/components/list/Sakoku.vue';
import Dlepus from '@/components/list/Dlepus.vue';
import Dlepuslogo from '@/components/list/Dlepuslogo.vue';
import Yokohamasho from '@/components/list/Yokohamasho.vue';
import Ccat from '@/components/list/Ccat.vue';
import Kurofune from '@/components/list/Kurofune.vue';
import Toratshop from '@/components/list/Toratshop.vue';
import Toratshoplogo from '@/components/list/Toratshoplogo.vue';
import Hdelicious from '@/components/list/Hdelicious.vue';
import Shizuku from '@/components/list/Shizuku.vue';
import Kyushoku from '@/components/list/Kyushoku.vue';
import Knuts from '@/components/list/Knuts.vue';
import Sanlogi from '@/components/list/Sanlogi.vue';
import Hantologo from '@/components/list/Hantologo.vue';
import Catbopost from '@/components/list/Catbopost.vue';
import Catbopamph from '@/components/list/Catbopamph.vue';
import Catbokaiin from '@/components/list/Catbokaiin.vue';
import Eastern from '@/components/list/Eastern.vue';
import Kamikochi from '@/components/list/Kamikochi.vue';


export default {
  layout: 'layout',
  name: 'IndexPage',
  components:{
    Hanto,
    Hantonew,
    Summer,
    Catbo,
    Yokohama,
    Newkoenji,
    Newkoenjilogo,
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
    Catbokaiin,
    Dlepuslogo,
    Eastern,
    Toratlogo,
    Toratshoplogo,
    Kamikochi
  }
}
</script>
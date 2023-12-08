<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import {ArrowLongRightIcon}  from '@heroicons/vue/24/outline'
</script>

<template>
  <div class="mt-36 mb-5">
    
      <span class="font-semibold text-orange-500">by maker of DiSC system </span> <br>
      <div class="mb-5">
        <span class="font-bold text-6xl">Build your new Vue <br> js app faster.</span> 
      </div>
    <span class=" text-2xl">Tailwind CSS's creators have created exquisitely <br> constructed components and templates. The ideal <br> place to start
      your next project.</span>
    
    
  </div>
  <button class="bg-orange-400 px-2 py-3 rounded-lg text-white shadow-md font-semibold flex">Browse Components <ArrowLongRightIcon class="h-6 w-6 text-slate-200 ml-2" /> </button>
</template>

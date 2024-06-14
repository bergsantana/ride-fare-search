<template>
    <div>
        <div class="  bg-black text-white h-24 w-[85vw] m-auto rounded-3xl" >
            
            <p class="pt-5  text-center text-2xl  first-letter:">
                Deseja gravar esta R$
                 
                    {{ thisFare.value }}
                
                pela Suber?

            </p>
        </div>
        <div class="flex text-8xl p-8 px-16 justify-between"> 
        <button class="text-bold text-gray-700 border-4  text-5xl border-solid border-gray-600 bg-gray-300 rounded-[20%] w-[25vw] ">
                No
            </button>
            <button class="p-2 border-4  bg-black text-white text-5xl border-solid border-black rounded-[20%] w-[25vw]">
               <NuxtLink to="">

                   Yes
               </NuxtLink>
            </button>
        </div>
    </div>
</template>

<script setup lang="ts">
const route = useRoute()
const { value:  thisFare}  = computed (() => route.query)
</script>
<template>
    <div>
        <div class="flex flex-col gap-2">
            <NuxtLink to="/ride">
                
            </NuxtLink>
            <button class="m-auto rounded-2xl">
                <NuxtLink to="/confirmation/fare?value=7.67">
                    <div class="flex py-1 px-3 h-12 w-[95vw] text-2xl bg-black border-2 border-white rounded-2xl  ">
                        <p class="w-[38vw] text-left">Suber</p>
                        <v-icon icon="mdi-motorbike" />
                        <p class="w-[35vw] text-right">R$ 7,67</p>
                    </div>
                </NuxtLink>
            </button>
            <button class="m-auto rounded-2xl">
                <div class="flex py-1 px-3 h-12 w-[95vw] text-2xl bg-yellow-400 border-2 border-white rounded-2xl  ">
                    <p class="w-[38vw] text-left font-bold">11Pipo</p>
                    <v-icon icon="mdi-motorbike" />
                    <p class="w-[35vw] text-right">R$ 8,03</p>
                </div>
            </button>
            <button class="m-auto rounded-2xl">
                <div class="flex py-1 px-3 h-12 w-[95vw] text-2xl bg-green-600 border-2 border-white rounded-2xl ">
                    <p class="w-[38vw] text-left font-mono">NoDriver</p>
                    <div class="  ">
                        <v-icon icon="mdi-car" />
                        <p class="w-[35vw] text-right">R$ 8,32</p>
                    </div>
                     
                </div>
            </button>
            <button class="m-auto rounded-2xl">
                <div class="flex py-1 px-3 h-12 w-[95vw] text-2xl bg-black border-2 border-white rounded-2xl">
                    <p class="w-[38vw] text-left">Suber</p>
                    <v-icon icon="mdi-car" />
                    <p class="w-[35vw] text-right">R$ 9,67</p>
                </div>
            </button>
        </div>
    </div>
    
</template>

<style></style>
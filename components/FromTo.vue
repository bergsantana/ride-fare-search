<template>
    <div>
        <div class="text-2xl w-[96vw] pl-9 font-serif font-bold border-b-2 pb-2 m-auto pt-9">
            <v-icon icon="mdi-map-marker-distance gpsicon" />
            <div class="grid grid-cols-[60px_1fr] px-4">
                <div>De</div>
                <input value="Av Torquato Tapajos 1999, Flores" class="pl-4 bg-white overflow-ellipsis rounded-xl w-full"/>
            </div>
            <div  class="grid grid-cols-[60px_1fr] px-4 mt-4">
                <div>Para</div>
                <input value="UEA-EST - Av Darcy" class="pl-4 overflow-ellipsis bg-white rounded-xl w-full" />
            </div>

        </div>
    </div>
</template>

<style>
.gpsicon{
    position: absolute;
    top: 52px;
    left: 12px;
}
</style>
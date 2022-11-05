<template>
    <div class="flex md:flex-row flex-col h-[70vh] w-screen justify-between items-center px-0 md:px-20">
        <div class=" flex flex-col w-full md:w-1/2 order-2 md:order-1 box-border px-5 md:px-0"> 
            <p class="text-4xl text-center md:text-left font-bold mb-1">Rio Juniyantara Putra</p>
            <p class="mb-6 text-center md:text-left">Web developer, Mobile developer</p>
            <button class="bg-[#FECE47] self-center md:self-start w-24 h-10 rounded-md cursor-pointer text-white font-bold">Klik Me</button>
        </div>

        <!-- image -->
        <div class="flex flex-row justify-center order-1 md:order-2 w-full md:w-1/2 md:h-3/4 h-2/3 overflow-hidden">
                <img src="https://images.pexels.com/photos/775358/pexels-photo-775358.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="" srcset="" class=" rounded-xl object-cover md:h-full h-full self-center md:w-full">
        </div>
    </div>
</template>

<script>
export default {
    name: 'Cta'
}
</script>
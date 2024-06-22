<template>
<div class="relative">
    <div class="sticky top-0 flex flex-col items-center justify-center">
        <div class="container mx-auto my-5">
        <div class="relative rounded-lg flex flex-col md:flex-row items-center md:shadow-xl md:h-72 mx-2">
            <div class="z-0 order-1 md:order-2 relative w-full md:w-2/5 h-80 md:h-full overflow-hidden rounded-lg md:rounded-none md:rounded-r-lg">
                <div class="absolute inset-0 w-full h-full object-none brightness-50  hover:blur-sm bg-blue-400 bg-opacity-30 bg-cover bg-bottom" style="background-image: url('./enjoy/house_woman.jpeg');"></div>
                <div class="md:hidden absolute text-yellow-500 inset-0 h-full p-6 pb-6 flex flex-col-reverse justify-start items-start  via-transparent to-gray-900">
                    <h3 class="w-full font-bold text-2xl text-yellow-500 leading-tight mb-2">ENJOY TOURISM</h3>
                    <h4 class="w-full text-xl text-gray-100 leading-tight ">GBES</h4>
                </div>
                <svg class="hidden md:block absolute inset-y-0 h-full w-24 fill-current text-white -ml-12" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <polygon points="50,0 100,0 50,100 0,100" />
                </svg>
            </div>

            <div class="z-10 order-2 md:order-1 w-full h-full md:w-3/5 flex items-center -mt-6 md:mt-0">
                <div class="p-8 md:pr-18 md:pl-14 md:py-12 mx-2 md:mx-0 h-full bg-white rounded-lg md:rounded-none md:rounded-l-lg shadow-xl md:shadow-none">
                    <h4 class="hidden md:block text-xl text-gray-400">GBES</h4>
                    <h3 class="hidden md:block font-bold text-2xl text-yellow-500">ENJOY TOURISM</h3>
              <p class="text-gray-600 text-justify">{"Nous sommes passionnés par la découverte du Congo profond et nous souhaitons partager la beauté de nos villes, de nos provinces et de nos sites touristiques avec le reste du monde. Notre pays regorge d'une nature diversifiée et unique, et nous voulons la faire connaître dans toute sa splendeur."}</p>
                    <a class="flex items-baseline mt-3 text-blue-600 hover:text-blue-900 focus:text-blue-900" href="">
                        <span>En savoir plus</span>
                        <span class="text-xs ml-1">&#x279c;</span>
                    </a>
                </div>
            </div>

        </div>
    </div>
    </div>
</div>
</template>
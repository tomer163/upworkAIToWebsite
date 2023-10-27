<template>
    <div class="absolute top-0 right-0 left-0 bottom-0 w-[1300px] h-[760px] m-auto">
        <div class="relative h-full w-full">
            <!--outer notebook-->
            <div class="overflow-hidden flex h-full rounded-r-3xl rounded-l shadow-[30px_35px_60px_-15px_rgba(0,0,0,1)]">
                <div class="h-full w-[28px] bg-[url('./assets/images/cork.jpg')] bg-left bg-cover bg-no-repeat shadow-[inset_-25px_0px_17px_-20px_rgba(0,0,0,0.7)] "></div>
                <div class="h-full w-[140px] bg-[url('./assets/images/leather.jpg')] bg-left bg-cover bg-no-repeat"></div>
                <div class="grow"></div>
                <div class="h-full w-[140px] bg-[url('./assets/images/orangeleather.jpg')] bg-[length:1100px] bg-left bg-cover bg-no-repeat">
                </div>
            </div>
            <!--right clasp-->
            <div class="absolute -right-5 w-[110px] h-[90px] top-0 bottom-0 m-auto rounded-l-full overflow-hidden shadow-[-1px_16px_20px_0px_rgba(0,0,0,0.7)]">
                    <div class="relative w-full h-full bg-[url('./assets/images/orangeleather2.jpeg')] bg-[length:400px] bg-top rounded-r-lg shadow-[inset_-30px_0px_30px_-20px_rgba(0,0,0,0.7)]">
                        <div class="w-[98%] h-full rounded-l-full border-l-[5px] border-t-[3px] border-b-[3px] border-[#dba48a]"></div>
                        <div class="absolute left-[35%] top-0 bottom-0 m-auto w-5 h-5 bg-[#e8b092] border border-[#5e483c] rounded-full shadow-[inset_0px_4px_5px_0px_rgba(0,0,0,1)] flex items-center ">
                            <div class="h-[3px] w-[3px] bg-black m-auto"></div>
                        </div>
                    </div>
            </div>
            <!--middle tablet(outer)-->
            <div class="absolute left-0 right-0 top-0 bottom-0 m-auto h-[105%] w-[80%] bg-[url('./assets/images/orangeleather.jpg')] bg-center bg-[length:780px] rounded-2xl shadow-[30px_50px_50px_-15px_rgba(0,0,0,0.7)] flex items-center border-y-[4px] border-x-[7px] border-orange-200">
                <!--middle tablet(inner)-->
                <div class="m-auto h-[85%] w-[90%] bg-orange-100 rounded-2xl shadow-[30px_35px_60px_-15px_rgba(0,0,0,1)] p-7">
                    <div class="flex flex-col text-center h-full">
                        <div class="flex items-center gap-10">
                            <button class="bg-stone-600 h-10 w-10 rounded-full text-white">yo</button>
                            <span class="font-bold">NOTE</span>
                        </div>
                        <h1 class="text-[80px] font-bold">Tools</h1>
                        <div class="grid grid-cols-3 grid-rows-4 h-full gap-y-6 gap-x-7">
                            <div class="w-[80%] h-[50%] mx-auto border-b-2 border-dotted border-b-stone-400"></div>
                            <div class="w-[70%] h-[50%] mx-auto border-b-2 border-dotted border-b-stone-400"></div>
                            <div class="w-[80%] h-[50%] mx-auto border-b-2 border-dotted border-b-stone-400"></div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                            <div class="bg-stone-600 rounded-xl">yo</div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                            <div class="bg-stone-600 rounded-xl">yo</div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                            <div class="bg-orange-200 rounded-xl">yo</div>
                        </div>
                        <div class="h-[250px] flex flex-col">
                            <div class="grow"></div>
                            <div class="h-20 border-t border-t-orange-200 flex items-center pt-6">
                                <button class="h-full w-40 rounded-full border-2 border-stone-600 flex overflow-hidden items-center text-white text-lg">
                                    <div class="h-full bg-stone-600 flex items-center w-[60%]">
                                        <span class="m-auto">OLLIL..</span>
                                    </div>
                                    <div class="text-stone-600 m-auto">
                                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
                                        </svg>
                                    </div>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
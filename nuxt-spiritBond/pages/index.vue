<template>
    <div class="bg-background-image flex flex-col items-center justify-center h-screen text-white">
        <h1 class="text-6xl font-serif font-bold tracking-widest mb-4 text-center" style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">SPIRIT BOUND</h1>
        <h4 class="text-xl font-serif font-extralight tracking-widest text-center">
            <!-- <span class="text-sm inline-block align-middle">&lt;&lt;</span>--> SURVIVE AND ESCAPE
            <!-- <span class="text-sm inline-block align-middle">&gt;&gt;</span>-->
        </h4>
        <div class="absolute bottom-6 mb-8">
            <button class="text-white font-bold py-2 px-2 animate-pulse" @click="nextSection()">More
                <svg class="w-6 h-6 animate-bounce mx-auto">
                    <path fill="currentColor" d="M5 9l7 7 7-7"></path>
                </svg>
            </button>
        </div>
    </div>
    <div class="min-h-screen bg-black text-white lg:flex lg:flex-inline">
        <div class="min-h-screen lg:w-1/2 w-full bg-gradient-to-br from-blue-600 to-blue-950 flex flex-col items-center justify-center">
            <h2 class="text-center text-5xl font-serif tracking-widest mt-9 pb-9"
                style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">SPIRIT BOUND</h2>
            <div class="inline-grid grid-cols-2 gap-3 lg:gap-9 mt-4">
                <div class="max-w-[300px] m-3 lg:m-6">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">DESCRIPTION</h3>
                    <p class="text-base">KB is a boy of dwarf race who
                        found in a world of giants, the
                        giants have taken away his sister and
                        You will have to find a way to meet her.</p>
                </div>
                <div class="max-w-[300px] m-3 lg:m-6">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">ABOUT THE STUDY</h3>
                    <p class="text-base">Studio Shonos is a studio founded in
                        December 2023 for a group of 4
                        students, our game SpiritBound
                        will present its first version on May 12
                        2024 after 5 months of development.</p>
                </div>
                <div class="max-w-[300px] m-3 lg:m-6">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">THE GAME</h3>
                    <p class="text-base">SpiritBound is an action and puzzle game
                        about some dwarfs in a world of
                        giants. <br>
                        Dessie is crucial to clear certain levels. <br>
                        Explore the various locations within
                        the house of the giants. <br>
                        Various control inputs including
                        Xbox Controller and Keyboard + Mouse</p>
                </div>
                <div class="max-w-[300px] m-3 lg:m-6">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">PEGI</h3>
                    <div class="inline-grid grid-cols-2 gap-5 m-3">
                        <img class="w-[75px]" src="public/assets/icons/12_PEGI.png" alt="Age_12">
                        <img class="w-[75px]" src="public/assets/icons/Discrimination_PEGI.jpg" alt="Discrimination">
                        <img class="w-[75px]" src="public/assets/icons/FEAR_PEGI.jpg" alt="Fear">
                        <img class="w-[75px]" src="public/assets/icons/Violence_PEGI.jpg" alt="Violence">
                    </div>
                </div>
            </div>
            <img class="max-w-[250px] max-h-[345px] -mt-9 -mb-4" src="public/assets/landing/SIBLINGS.png" alt="The brothers">
        </div>
        <div class="min-h-screen py-9 lg:w-1/2 w-full flex flex-col items-center justify-center">
            <div class="inline-grid grid-cols-2 gap-3">
                <div class="lg:min-w-[250px] lg:h-[175px] bg-gradient-to-br from-blue-600 to-black p-4">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">KB</h3>
                    <p class="text-base ml-3">
                        GENTLE <br>
                        PEACEFUL <br>
                        DWARF
                    </p>
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px]">
                    <img class="lg:ml-9 -mt-3 max-w-[210px]" src="public/assets/landing/KB02.png" alt="KB">
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px]">
                    <img class="lg:mr-9 -mt-3 max-w-[250px]" src="public/assets/landing/DESSIE.png" alt="DESSIE">
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px] bg-gradient-to-br from-blue-600 to-black p-4">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">DESSIE</h3>
                    <p class="text-base ml-3">
                        BRAVE <br>
                        INTELLIGENT <br>
                        AGILE <br>
                        DWARF
                    </p>
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px] bg-gradient-to-br from-blue-600 to-black p-4">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">GREN</h3>
                    <p class="text-base ml-3">
                        ANTON'S OWNER <br>
                        LAZY <br>
                        IRASCIBLE <br>
                        GIANT
                    </p>
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px]">
                    <img class="lg:ml-9 -mt-3 max-w-[210px]" src="public/assets/landing/GREN.png" alt="GREN">
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px]">
                    <img class="lg:mr-9 -mt-2 max-w-[240px]" src="public/assets/landing/ANTON.png" alt="ANTON">
                </div>
                <div class="lg:min-w-[250px] lg:h-[175px] bg-gradient-to-br from-blue-600 to-black p-4">
                    <h3 class="text-2xl font-serif tracking-widest pb-3"
                        style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">ANTON</h3>
                    <p class="text-base ml-3">
                        INDEPENDENT <br>
                        LAZY <br>
                        GIANT
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    methods: {
        nextSection() {
            window.scrollTo({
                top: window.innerHeight,
                behavior: 'smooth'
            });
        }
    }
}
</script>

<style scoped>
.bg-background-image {
    background-image: url("public/assets/backgrounds/BACKGROUND.png");
    background-size: cover;
    background-position: center;
}
</style>
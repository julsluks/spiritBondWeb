<template>
    <div
        class="min-h-screen w-full bg-gradient-to-br from-blue-600 to-blue-950 flex flex-col items-center justify-center text-white">
        <div class="mt-9 pt-9">
            <h1 class="text-6xl font-serif font-bold tracking-widest mb-4 text-center mt-9"
            style="text-shadow: 5px 3px 4px rgba(255, 255, 255, 0.9);">HOW TO PLAY</h1>
        </div>
        <div class="min-h-1/2 w-full mt-6 mb-4">
            <div class="flex flex-col items-center justify-center m-4">
                <p class="text-lg tracking-widest mb-4 text-center bg-blue-950 bg-opacity-30 p-5 rounded-lg">
                    It's played using the keyboard. With the
                    “A” key to move left, the “D” key to move right, <br> and if you press “Shift” you can change the
                    character's action from walking to running. <br> The space bar is for jumping, with the “E” key we
                    interact with the objects in the video game,<br> while with the “Q” we summon the sister and crouch with
                    the control,<br> we also want to implement an Xbox controller.
                </p>
                <p class="text-lg tracking-widest mb-4 text-center bg-blue-950 bg-opacity-30 p-5 rounded-lg">
                    To play with a controller, the square is used to interact and the <br> “X” is used to jump, and the left joystick is used to walk/run.
                </p>
            </div>
            <div class="lg:flex lg:items-center lg:justify-center mt-9">
                <div class="lg:w-1/4 mx-4 my-4 flex items-center justify-center">
                    <img src="public/assets/howToPlay/keyboard.png" alt="Keyboard">
                </div>
                <div class="lg:w-1/2 lg:min-w-[610px] lg:min-h-[365px] md:min-w-[410px] md:min-h-[250px] mx-4 my-4 flex items-center justify-center">
                    <iframe class="lg:w-1/2 lg:min-w-[610px] lg:min-h-[365px] md:min-w-[410px] md:min-h-[250px]" src="https://www.youtube-nocookie.com/embed/_QdnSEdgsCo?si=CBVU74XmYlOEIKHd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </div>
                <div class="lg:w-1/4 mx-4 my-4 flex items-center justify-center">
                    <img src="public/assets/howToPlay/gamePadXbox.png" alt="Xbox Controller">
                </div>
            </div>
        </div>
    </div>
</template>

<template>
    <section class="relative w-full flex gap-5 flex-col justify-center items-center bg-[#070707] py-32 overflow-hidden px-2">
        <img class="w-full max-w-6xl absolute -left-48 -top-96 mix-blend-screen" src="@/assets/images/light_blur_division.png" />

        <div class="lg:hidden relative w-full max-w-5xl h-80 bg-blinkyLittleBege flex justify-center rounded-3xl">
            <img class="absolute bottom-0 w-full min-w-[48.5rem] max-w-[48.5rem]" src="@/assets/images/woman_with_icon.png" />
        </div>

        <div class="relative w-full max-w-5xl h-80 bg-blinkyLittleBege flex items-center rounded-3xl p-2 sm:p-14">
            <div class="w-full lg:w-fit flex gap-5 flex-col justify-center items-center lg:items-start">
                <h3 class="font-poppins font-semibold text-xl sm:text-3xl text-center lg:text-left">
                    Conecte-se e potencialize <br>
                    seus negócios conosco!
                </h3>

                <p class="font-poppins font-light text-[11px] sm:text-base text-center lg:text-left">
                    Descubra como a Blinky pode transformar a maneira <br>
                    como você conduz seus negócios. Conecte-se conosco <br>
                    hoje e abra as portas para um futuro de prosperidade.
                </p>

                <a class="hoverAnimation flex gap-3 items-center font-poppins text-black font-semibold bg-gradient-to-r from-blinkyBlue to-blinkyGreen px-12 py-1.5 rounded-lg">
                    Fale Conosco
                    <IconsArrowForward width="20" height="20" stroke="#000" />
                </a>
            </div>

            <img class="hidden lg:block absolute bottom-0 -right-32 w-full max-w-[48.5rem]" src="@/assets/images/woman_with_icon.png" />
        </div>
    </section>
</template>
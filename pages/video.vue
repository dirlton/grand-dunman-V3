<template>
  <div>
    <div class="py-12 select-none bg-theme-700">
      <div class="text-xl font-semibold text-center text-white sm:text-4xl">
        Video
      </div>
    </div>
    <section>
      <div class="max-w-6xl px-4 py-12 mx-auto space-y-6">
        <p class="max-w-2xl mx-auto text-center">
          </p>
          <iframe
              loop="1"
              width="1000"
              height="600"
              class="mx-auto"
              src="https://www.youtube.com/embed/LMahLA_6Ekg"
              title="Grand Dunman Videos"
              frameborder="0"
              allow="accelerometer;
              autoplay;
              clipboard-write;
              encrypted-media;
              gyroscope;
              picture-in-picture"
              allowfullscreen
            ></iframe>
        <h3 class="text-center"> Source and Credit from <a target="_blank" class="transition text-theme-600 hover:text-theme-700" href="https://www.youtube.com/@granddunman4811">Grand Dunman</a></h3>
        <section class="py-6">
          <NuxtLink
            to="/e-brochure"
            class="
              inline-flex
              items-center
              justify-center
              w-full
              px-3
              py-3
              text-white
              transition
              rounded
              sm:px-0
              hover:bg-theme-900
              bg-theme-700
            "
          >
            Continue To E-Brochures
            <svg
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              class="w-5 h-5"
            >
              <path
                d="M13 6l6 6-6 6M5 6l6 6-6 6"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              </svg>
              </NuxtLink>
        </section>
      </div>
    </section>
    <BookAppointment />
  </div>
</template>

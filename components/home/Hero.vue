<template>
  <section class="relative bg-white overflow-hidden dark:bg-main-700">
    <div class="max-w-screen-xl mx-auto">
      <div
        class="relative z-10 py-8 lg:py-12 bg-white dark:bg-main-700 lg:max-w-2xl lg:w-full flex items-center"
      >
        <svg
          class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2 dark:text-main-700"
          fill="currentColor"
          viewBox="0 0 100 100"
          preserveAspectRatio="none"
        >
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>

        <main class="mx-auto max-w-screen-xl p-4 sm:p-6 lg:p-8">
          <div class="sm:text-center lg:text-left">
            <h2
              class="text-5xl font-main tracking-tight leading-10 text-gray-900 sm:leading-none md:text-6xl dark:text-gray-200"
            >
              Un Compendio
              <br class="xl:hidden" />
              <span class="text-secondary-600">de material </span>
            </h2>
            <p
              class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0 dark:text-gray-300"
            >
              Todo lo que bucas. Mucho de lo que queres. Y en tu idioma. <wbr />
              Contenido de primera para tus juegos de Rol, Uses el sistmea que
              uses y jueges como juegeues.
            </p>
            <div
              class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start"
            >
              <div class="rounded-md shadow">
                <nuxt-link to="/retainers" class="main-btn">
                  Empezar!
                </nuxt-link>
              </div>
              <!-- <div class="mt-3 sm:mt-0 sm:ml-3">
                <nuxt-link
                  to="#"
                  class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-secondary-700 bg-secondary-100 hover:text-secondary-600 hover:bg-secondary-50 focus:outline-none focus:shadow-outline-secondary focus:border-secondary-300 transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10"
                  disabled
                >
                  Register
                </nuxt-link>
              </div> -->
            </div>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img
        class="h-56 w-full object-cover object-right sm:h-72 md:h-96 lg:w-full lg:h-full"
        src="@/assets/images/DnD_DMG_Art.jpg"
        alt="Image of the Dungeon Master Guide"
      />
    </div>
  </section>
</template>

<style scoped>
.main-btn {
  @apply w-full flex items-center justify-center px-8 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-secondary-600 transition duration-150 ease-in-out;
}
.main-btn:hover {
  @apply bg-secondary-500;
}
.main-btn:focus {
  @apply outline-none border-secondary-700;
}
/* shadow-outline-secondary */
@media screen and (min-width: 768px) {
  .main-btn {
    @apply py-4 text-lg px-10;
  }
}
</style>

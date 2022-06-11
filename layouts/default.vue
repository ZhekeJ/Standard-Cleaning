<template>
  <div>
    <div class="mt-0">
      <header class="bg-indigo-300 ">
        <nav class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8" aria-label="Top">
          <div
            class="flex items-center justify-between w-full py-6 border-b border-indigo-500 lg:border-none"
          >
            <div class="flex items-center">
              <a class="rounded-md" href="/">
                <span class="sr-only">Workflow</span>
                <img
                  class="w-24 h-10 "
                  src="~/assets/img/logo1.png"
                  alt=""
                />
              </a>
              <div class="hidden ml-10 space-x-8 lg:block">
                <a
                  href="/"
                  class="text-base font-medium text-red-600 hover:text-indigo-50"
                >
                  Home
                </a>
                <a
                  href="/services"
                  class="text-base font-medium text-red-600 hover:text-indigo-50"
                >
                  Services
                </a>
               
                <a
                  href="/about"
                  class="text-base font-medium text-red-600 hover:text-indigo-50"
                >
                  About Us
                </a>

                <a
                  href="/contact"
                  class="text-base font-medium text-red-600 hover:text-indigo-50"
                >
                  Contact Us
                </a>
              </div>
            </div>
            <div
              class="mt-2 max-w-sm mx-auto sm:max-w-none sm:flex sm:justify-center"
            >
              <div
                class="space-y-4 sm:space-y-0 sm:mx-auto sm:inline-grid sm:grid-cols-2 sm:gap-5"
              >
                <a
                  href="/commercial"
                  class="flex items-center justify-center px-4 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-red-600 hover:bg-indigo-500 sm:px-8"
                >
                  Commercial Cleaning
                </a>
                <a
                  href="/residential"
                  class="flex items-center justify-center px-4 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-indigo-500 bg-opacity-60 hover:bg-opacity-70 sm:px-8"
                >
                  Residential Cleaning
                </a>
              </div>
            </div>
          </div>
          <div
            class="flex flex-wrap justify-start py-4 space-x-2 ml-3 lg:hidden"
          >
            <a
              href="/"
              class="text-base font-medium underline text-white hover:text-indigo-50"
            >
              Home
            </a>

            <a
              href="/services"
              class="text-base font-medium underline text-white hover:text-indigo-50"
            >
              Services
            </a>

            <a
              href="/about"
              class="text-base font-medium underline text-white hover:text-indigo-50"
            >
              About Us
            </a>
            <a
              href="/contact"
              class="text-base font-medium underline text-white hover:text-indigo-50"
            >
              Contact Us
            </a>
          </div>
        </nav>
      </header>
    </div>

    <div class="">
      <!--</main> -->
      <Nuxt />
    </div>

    <div class="mt-0">
      <Footer />
    </div>
  </div>
</template>

<script>
</script>

<style>
/* home route and active route will show in bold as it matches / and /NuxtLinkbout */
a.nuxt-link-active {
  font-weight: 900;
  color: #1aa7ec;
}
/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
  color: #1aa7ec;
}
</style>

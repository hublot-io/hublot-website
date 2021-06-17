<template>
  <footer class="bg-hublot-100 w-full rounded-t-3xl">
    <div class="container mx-auto px-4">
      <div class="sm:flex sm:flex-wrap sm:-mx-4 md:py-4">
        <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6">
          <h5 class="text-white text-xl font-bold mb-6">Features</h5>
          <ul class="list-none footer-links">
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Cool stuff</a>
            </li>
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Random feature</a>
            </li>
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Team feature</a>
            </li>
          </ul>
        </div>
        <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 sm:mt-0">
          <h5 class="text-white text-xl font-bold mb-6">Ressources</h5>
          <ul class="list-none footer-links">
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Mentions légales</a>
            </li>
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">RGPD</a>
            </li>
          </ul>
        </div>
        <div class="px-4 sm:w-1/2 md:w-1/4 xl:w-1/6 mt-8 md:mt-0">
          <h5 class="text-white text-xl font-bold mb-6">À propos</h5>
          <ul class="list-none footer-links">
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Team</a>
            </li>
            <li class="mb-2">
              <a href="#" class="border-b border-solid border-transparent hover:border-purple-800 hover:text-purple-800">Locations</a>
            </li>
          </ul>
        </div>
        <div class="px-4 mt-4 sm:w-1/3 xl:w-1/6 sm:mx-auto xl:mt-0 xl:ml-auto">
          <h5 class="text-white text-xl font-bold mb-6 sm:text-center xl:text-left">Suivez-nous</h5>
          <div class="flex sm:justify-center xl:justify-start">
            <a href="https://www.twitter.com/Hublot_SAS" target="_blank" class="w-12 h-12 place-items-center border hover:border-2 border-white-400 rounded-full text-center   hover:text-white">
              <font-awesome-icon :icon="['fab','twitter']" class="social-icon" />
            </a>
            <a href="https://www.linkedin.com/company/hublot-io" target="_blank" class=" w-12 h-12 border hover:border-2 border-white-400 rounded-full text-center  ml-4  hover:text-white">
              <font-awesome-icon :icon="['fab','linkedin']" class="social-icon" />
            </a>
          </div>
        </div>
      </div>

      <div class="text-white sm:flex sm:flex-wrap sm:-mx-4 mt-6 pt-6 sm:mt-12 sm:pt-12 border-t">
        <div class="sm:w-full px-4 md:w-1/6">
          <strong>Hublot SAS</strong>
        </div>
        <div class="px-4 sm:w-1/2 md:w-1/4 mt-4 md:mt-0">
          <h6 class="text-white font-bold mb-2">Adresse</h6>
          <address class="not-italic mb-4 text-sm">
            Le Palace<br>
            4, rue Voltaire<br>
            44000 - NANTES
          </address>
        </div>
        <div class="px-4 md:w-1/4 md:ml-auto mt-6 sm:mt-4 md:mt-0">
          <button class="px-4 py-2 bg-white text-primary rounded transform transform motion-safe:hover:scale-110">Je veux essayer</button>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="postcss" scoped>
.social-icon {
  font-size: 1.6rem;
}
</style>

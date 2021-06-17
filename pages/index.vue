<template>
  <main>
    <div class="h-screen">
      <section class="self-center flex flex-col flex-1 items-center justify-center">
        <h1 class="title text-center">HUBLOT</h1>
        <h2 class="subtitle text-center">La marée, autrement</h2>
      </section>

      <section class="mt-8 absolute inset-x-0 bottom-0">
        <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Nos derniers articles</h3>
        <posts post-type="blog" :amount="2" />
      </section>
    </div>
  </main>
</template>
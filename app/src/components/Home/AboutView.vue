<template>
  <div id="aboutSection" class="container mx-auto pt-60 px-8 max-sm:pt-32">
    <section class="">
      <div class="mx-auto">
        <div class="max-w-screen-md">
          <h2
            class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white"
          >
            Gravação e Desenho Têxtil.
          </h2>
          <p
            class="mb-8 font-light text-gray-500 sm:text-xl dark:text-gray-400"
          >
            A gravação e o design têxtil são técnicas artesanais que permitem
            criar desenhos e textos em superfícies diversas. A gravação pode ser
            feita em metal, madeira, vidro e até mesmo em alguns tipos de
            tecido, enquanto o design têxtil é especialmente aplicado em tecidos
            para criar estampas e padrões.
          </p>
          <div
            class="flex flex-col space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4"
          >
            <router-link
              to="/about"
              class="inline-flex items-center justify-center px-4 py-2.5 text-base font-medium text-center text-white bg-primary-700 rounded-lg hover:bg-sky-700 dark:focus:ring-primary-900"
            >
              Saber Mais
              <svg
                class="ml-2 -mr-1 w-5 h-5"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </router-link>
            <a
              href="https://www.youtube.com/@joanigrave"
              target="_blank"
              class="inline-flex items-center justify-center px-4 py-2.5 text-base font-medium text-center text-gray-900 border border-gray-300 rounded-lg hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 dark:text-white dark:border-gray-600 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
            >
              <svg
                class="mr-2 -ml-1 w-5 h-5"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M2 6a2 2 0 012-2h6a2 2 0 012 2v8a2 2 0 01-2 2H4a2 2 0 01-2-2V6zM14.553 7.106A1 1 0 0014 8v4a1 1 0 00.553.894l2 1A1 1 0 0018 13V7a1 1 0 00-1.447-.894l-2 1z"
                ></path>
              </svg>
              Vídeos
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

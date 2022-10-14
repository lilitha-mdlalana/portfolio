<script setup>

const projects = [
  {
    id: 1,
    imagePath: "/images/projects/oDelivery.jpg",
    projectName: "oDelivery",
    projectStack: "TailwindCSS and Nuxt 2",
    projectDescription:
      "A delivery startup landing page built to convert visitors into customer. The goal of this landing page is to provide a simple, no-nonsense user experience that highlights the company's products and services.",
    liveSiteLink: "https://odelivery.netlify.app",
    githubLink: "https://github.com/lilitha-mdlalana/odelivery-landing-page",
  },
  {
    id: 2,
    imagePath: "/images/projects/appy.jpg",
    projectName: "Appypot",
    projectStack: "TailwindCSS,Nuxt 3 and ButterCMS",
    projectDescription:
      "A self-platform landing page for small business owners to grow their business. The landing page includes a blog feature that utilises a headless CMS as it's backend.",
    liveSiteLink: "https://appypot.netlify.app/",
    githubLink: "https://github.com/lilitha-mdlalana/appypot-cms-landing-page",
  },
  {
    id: 3,
    imagePath: "/images/projects/sneaker-link.jpg",
    projectName: "SneakerLink w/ API ( IN PROGRESS )",
    projectStack: "BulmaCSS, Nuxt 3 and Pinia",
    projectDescription:
      "SneakerLink is a product listing website that fetches products from an API and renders them. With a simple interface, the site allow users to add items to cart and checkout in seconds.",
    liveSiteLink: "https://sneaker-link.netlify.app/",
    githubLink: "https://github.com/lilitha-mdlalana/sneaker-link",
  },
];
</script>

<template>
  <main>
    <Head>
      <Title>Lilitha Mdlalana - Profile</Title>
      <Link rel="icon" type="image/x-icon" href="/favicon.ico" />
    </Head>
    <section
      class="dark:bg-gray-800 font-mono bg-white relative overflow-hidden"
    >
      <div class="hidden md:block absolute -bottom-32 -left-32 w-96 h-96">
        <div
          class="absolute text-extrabold text-xl right-12 z-20 text-start top-1/4"
        ></div>
        <svg
          viewBox="0 0 200 200"
          class="absolute w-full h-full"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            fill="#FFDBB9"
            d="M44.7,-76.4C58.8,-69.2,71.8,-59.1,79.6,-45.8C87.4,-32.6,90,-16.3,88.5,-0.9C87,14.6,81.4,29.2,74.1,43.2C66.7,57.2,57.6,70.6,45,78.1C32.4,85.6,16.2,87.1,0.7,85.9C-14.8,84.7,-29.6,80.9,-43.9,74.4C-58.3,67.9,-72,58.7,-79.8,45.9C-87.7,33,-89.5,16.5,-88.9,0.3C-88.4,-15.9,-85.4,-31.7,-78.1,-45.4C-70.8,-59.1,-59.1,-70.6,-45.3,-77.9C-31.6,-85.3,-15.8,-88.5,-0.3,-88.1C15.3,-87.6,30.5,-83.5,44.7,-76.4Z"
            transform="translate(100 100)"
          ></path>
        </svg>
      </div>
      <header class="h-24 sm:h-32 flex items-center z-30 w-full">
        <div class="container mx-auto px-6 flex items-center justify-between">
          <div
            class="uppercase text-gray-800 dark:text-white font-black text-3xl flex items-center"
          >
            <svg
              width="25"
              height="25"
              viewBox="0 0 1792 1792"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M1664 1504v-768q-32 36-69 66-268 206-426 338-51 43-83 67t-86.5 48.5-102.5 24.5h-2q-48 0-102.5-24.5t-86.5-48.5-83-67q-158-132-426-338-37-30-69-66v768q0 13 9.5 22.5t22.5 9.5h1472q13 0 22.5-9.5t9.5-22.5zm0-1051v-24.5l-.5-13-3-12.5-5.5-9-9-7.5-14-2.5h-1472q-13 0-22.5 9.5t-9.5 22.5q0 168 147 284 193 152 401 317 6 5 35 29.5t46 37.5 44.5 31.5 50.5 27.5 43 9h2q20 0 43-9t50.5-27.5 44.5-31.5 46-37.5 35-29.5q208-165 401-317 54-43 100.5-115.5t46.5-131.5zm128-37v1088q0 66-47 113t-113 47h-1472q-66 0-113-47t-47-113v-1088q0-66 47-113t113-47h1472q66 0 113 47t47 113z"
              ></path>
            </svg>
            <a href="mailto:innomdlalana@gmail.com" class="text-xs ml-3 mt-1">
              innomdlalana@gmail.com
            </a>
          </div>
          <div
            class="flex items-center"
          >
            <nav
              class="font-sen text-gray-800 dark:text-white uppercase text-lg lg:flex items-center hidden"
            >
              <a href="#projects" class="py-2 px-6 flex hover:text-black">
                Projects
              </a>
              <a href="#about" class="py-2 px-6 flex hover:text-black">
                About
              </a>
            </nav>
          </div>
        </div>
      </header>

      <div class="flex relative z-20 items-center">
        <div
          class="container mx-auto px-6 flex flex-col justify-between items-center relative py-4"
        >
          <div class="flex flex-col">
            <img
              src="/images/person/personality-icon.png"
              class="rounded-full w-28 mx-auto"
            />
            <p class="text-3xl my-6 text-center dark:text-white">
              Hi, I&#x27;m Lilitha 🤘
            </p>
            <h2
              class="max-w-3xl text-5xl md:text-6xl font-bold mx-auto dark:text-white text-gray-800 text-center py-2"
            >
              Front-end web developer with a focus on Vue.js
            </h2>
            <div class="flex items-center justify-center mt-4">
              <a
                href="https://linkedin.com/in/lilitha-mdlalana"
                class="mx-1 uppercase py-2 my-2 px-4 md:mt-16 bg-transparent dark:text-gray-800 dark:bg-white hover:dark:bg-gray-100 border-2 border-gray-800 text-gray-800 dark:text-white hover:bg-gray-800 hover:text-white text-md"
              >
                CONNECT WITH ME
              </a>
              <a
                download
                href="/files/lilitha-mdlalana-cv.pdf"
                class="mx-1 uppercase py-2 my-2 px-4 md:mt-16 bg-transparent dark:text-gray-800 dark:bg-white hover:dark:bg-gray-100 border-2 border-gray-800 text-gray-800 dark:text-white hover:bg-gray-800 hover:text-white text-md"
              >
                RESUME
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="projects" class="mt-6">
      <h1 class="text-3xl font-bold text-center">Projects</h1>
      <div class="mt-8 grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3">
        <ProjectCard
          v-for="project in projects"
          :key="project.id"
          :image-path="project.imagePath"
          :project-name="project.projectName"
          :project-stack="project.projectStack"
          :project-description="project.projectDescription"
          :live-link="project.liveSiteLink"
          :github-link="project.githubLink"
        />
      </div>
    </section>
    <section id="about">
      <section>
        <div class="mx-auto max-w-screen-xl px-4 py-16 sm:px-6 lg:px-8">
          <div class="grid grid-cols-1 gap-8 lg:grid-cols-2 lg:gap-16">
            <div
              class="relative h-64 overflow-hidden rounded-lg sm:h-80 lg:order-last lg:h-full"
            >
              <img
                alt="Party"
                src="/images/me.jpg"
                class="h-[500px] object-cover rounded-full"
              />
            </div>

            <div class="lg:py-24">
              <h2
                class="max-w-3xl text-5xl md:text-6xl font-bold mx-auto text-gray-800 py-2"
              >
                Hi, I'm Lilitha 👨‍💻
              </h2>

              <p class="mt-4 text-gray-600">
                I'm a skilled and creative web developer based in Cape Town,
                South Africa. I build and design user-friendly websites and
                applications, while also keeping accessabilty in mind.
              </p>
              <p class="mt-4 text-gray-600">
                I have been programming since I was 13 years old. I started out
                by building games using Python and PyGame for my friends and I.
                Later, I began making building websites for my friends and local
                companies in my area.
              </p>
              <p class="mt-4 text-gray-600">
                Some of my skills include: HTML/CSS, JavaScript, Vue, Nuxt,
                Pinia and Webflow. I am always up for learning something new!
              </p>
            </div>
          </div>
        </div>
      </section>
    </section>
    <footer id="contact" class="bg-white text-center dark:bg-gray-900">
      <div class="mx-auto max-w-screen-xl px-4 py-12 sm:px-6 lg:px-8">
        <div class="mx-auto max-w-3xl space-y-6">
          <div class="flex justify-center gap-6">
            <a
              class="text-blue-500 hover:text-blue-500/75"
              href="https://twitter.com/dev_litha"
              target="_blank"
              rel="noreferrer"
              aria-label="Twitter"
            >
              <svg
                class="h-8 w-8"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
                ></path>
              </svg>
            </a>

            <a
              class="text-gray-900 hover:text-gray-900/75 dark:text-gray-300 dark:hover:text-gray-300/75"
              href="https://github.com/lilitha-mdlalana"
              target="_blank"
              rel="noreferrer"
              aria-label="GitHub"
            >
              <svg
                class="h-8 w-8"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                  clip-rule="evenodd"
                ></path>
              </svg>
            </a>

            <a
              class="text-pink-600 hover:text-pink-600/75"
              href="https://linkedin.com/lilitha-mdlalana/"
              target="_blank"
              rel="noreferrer"
              aria-label="LinkedIn"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="35"
                viewBox="0 0 24 24"
              >
                <path
                  d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
                />
              </svg>
            </a>
          </div>
          <p>&copy; 2022 Lilitha Mdlalana</p>
        </div>
      </div>
    </footer>
  </main>
</template>
<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style>

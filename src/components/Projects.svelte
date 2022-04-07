<script>
  let pr1 = "/magic.avif";
  let pr2 = "/school.avif";
  let pr3 = "/church.avif";
</script>

<section class="animate__fadeInUpBig ml-24 py-24" id="projects">
  <h3 class="text-3xl font-bold text-gray-200 py-10">
    My projects _________________
  </h3>
  <div class="grid grid-cols-1 gap-1 md:grid-cols-3 pr-10">
    <a href="https://magicmoving.co.ke/" target="blank">
      <div class="flex items-center justify-center">
        <card class="relative h-[30rem] sm:h-96 w-[35rem] rounded-lg">
          <!-- Background Image -->
          <img src={pr1} class="object-cover w-full h-full rounded-lg" alt="" />

          <!-- Content -->
          <div
            class="bg-gray-900 absolute w-full h-full bottom-0 bg-gradient-to-r from-fuchsia-700/30 to-violet-700 rounded-lg flex flex-col items-center justify-center text-center hover:bg-gray-700 animate-pulse"
          >
            <h1 class="text-3xl font-bold">Business Website</h1>

            <!-- Quotes -->
            <p class="text-lg px-14 text-gray-300 mt-10">Magic Movers</p>
          </div>
        </card>
      </div>
    </a>
    <a href="https://magicmoving.co.ke/">
      <div class="flex items-center justify-center">
        <card class="relative h-[30rem] sm:h-96 w-[35rem] rounded-lg">
          <!-- Background Image -->
          <img src={pr2} class="object-cover w-full h-full rounded-lg" alt="" />

          <!-- Content -->
          <div
            class="bg-gray-900 absolute w-full h-full bottom-0 bg-gradient-to-r from-fuchsia-700/30 to-violet-700 rounded-lg flex flex-col items-center justify-center text-center hover:bg-gray-700 animate-pulse"
          >
            <h1 class="text-3xl font-bold">School Website</h1>

            <!-- Quotes -->
            <p class="text-lg px-14 text-gray-300 mt-10">skoolite</p>
          </div>
        </card>
      </div>
    </a>
    <a href="https://jccksm.netlify.com" target="blank">
      <div class="flex items-center justify-center cursor-pointer">
        <card class="relative h-[30rem] sm:h-96 w-[35rem] rounded-lg">
          <!-- Background Image -->
          <img src={pr3} class="object-cover w-full h-full rounded-lg" alt="" />

          <!-- Content -->
          <div
            class="bg-gray-900 absolute w-full h-full bottom-0 bg-gradient-to-r from-fuchsia-700/30 to-violet-700 rounded-lg flex flex-col items-center justify-center text-center hover:bg-gray-700 animate-pulse"
          >
            <h1 class="text-3xl font-bold">Church Website</h1>

            <!-- Quotes -->
            <p class="text-lg px-14 text-gray-300 mt-10">JCC Kisumu</p>
          </div>
        </card>
      </div>
    </a>
  </div>
</section>

<!--<script>
  import ProjectsCard from "./cards/ProjectsCard.svelte";

  const projects = [
    {
      id: 1,
      title: "Library API",
      description: `Get any book by searching with any letter,its serial number
        or date published.`,
      mode: "#NodeJS  #ExpressJs  #MongoDB",
    },
    {
      id: 2,
      title: "House Search API",
      description: `An API With jwt authentication with user login
        rights.
           A user can find a House Post a New House
            Or Update in the App.`,
      mode: "#NodeJS  #ExpressJs  #MongoDB",
    },
    {
      id: 2,
      title: "Job Search API",
      description: `An API With jwt authentication with user login
        rights.
           A user can find a Job Post a New Job
            Or Update Job in the API.`,
      mode: "#NodeJS  #ExpressJs  #MongoDB",
    },
  ];
</script>

<section id="projects">
  <div class="ml-24 py-24 pt-0">
    <h3 class="text-3xl font-bold text-gray-200 py-6">
      My Projects _________________
    </h3>
    <div class="flex flex-row flex-wrap justify-evenly sm:gap-5">
      {#each projects as project}
        <ProjectsCard {...project} />
      {/each}
    </div>
  </div>
</section> -->

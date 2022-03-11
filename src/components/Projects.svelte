<script>
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
</section>

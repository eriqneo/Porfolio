<script>
  let src = "/face";
  let menuShow = false;

  function toggleNavbar() {
    menuShow = !menuShow;
  }
</script>

<section id="home">
  <div class="flex flex-wrap py-2 sticky top-0">
    <div class="w-full px-4 ">
      <nav
        class="relative flex flex-wrap items-center justify-between px-2 py-3 navbar-expand-lg rounded"
      >
        <div
          class="container px-4 mx-auto flex flex-wrap items-center justify-between"
        >
          <div
            class="w-full relative flex justify-between lg:w-auto px-4 lg:static lg:block lg:justify-start"
          >
            <a class="flex flex-row gap-2" href="#home">
              <img {src} alt="logo" class="w-16 rounded-full backdrop-sepia " />
              <p class="text-2xl pt-7"><strong>EriQ NeO...</strong></p>
            </a>
            <button
              class="text-white cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
              type="button"
              on:click={toggleNavbar}
            >
              <img src="/ham.jpg" alt="" class="w-10" />
            </button>
          </div>
          <div
            class="lg:flex lg:flex-grow items-center {menuShow
              ? 'flex'
              : 'hidden'}"
          >
            <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
              <li class="nav-item">
                <a
                  class="px-3 py-2 flex items-center text-sm uppercase font-bold leading-snug text-white hover:text-green-400"
                  href="#about"
                >
                  About
                </a>
              </li>
              <li class="nav-item">
                <a
                  class="px-3 py-2 flex items-center text-sm uppercase font-bold leading-snug text-white hover:text-green-400"
                  href="#experience"
                >
                  Process
                </a>
              </li>
              <li class="nav-item">
                <a
                  class="px-3 py-2 flex items-center text-sm uppercase font-bold text-white hover:text-green-400"
                  href="#projects"
                >
                  Projects
                </a>
              </li>
              <li class="nav-item">
                <a
                  class="px-3 py-2 flex items-center text-sm uppercase font-bold text-white hover:text-green-400"
                  href="#services"
                >
                  My Services
                </a>
              </li>
              <li class="nav-item">
                <a
                  class="px-3 py-2 flex items-center text-sm uppercase font-bold leading-snug text-white hover:text-green-400"
                  href="#contact"
                >
                  Contact
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</section>

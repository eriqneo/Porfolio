<script>
  let src = "/email.png";
</script>

<main id="contact">
  <div class="ml-24 py-24 pt-16">
    <h3 class="text-3xl font-bold text-gray-200">
      Contact Me _________________
    </h3>
    <p class="text-center pt-4 text-gray-200">
      I am Excited to build you in the web. <br /> It feels very nice when
      anyone in <br />
      the world could see your business just by a visit to the web. <br />
      Feel free to ask any question and I will be in touch as soon as possible.😊
    </p>
    <div class="pt-3 flex flex-row space-x-40 justify-items-center">
      <img {src} alt="email" class="lg:w-2/5 hidden md:block" />

      <form action="https://formspree.io/f/moqrwdwb" method="POST">
        <div>
          <label for="fname" class="text-gray-200">First Name</label>
          <input
            type="text"
            id="fname"
            name="firstname"
            placeholder="Your First Name"
            required
            class="w-full text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline bg-green-100"
          />
          <label for="lname" class="text-gray-200 pt-3">Last Name</label>
          <input
            type="text"
            id="lname"
            name="lastname"
            placeholder="Your Last Name"
            class="w-full text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline bg-green-100"
          />
          <label for="lname" class="text-gray-200 pt-3">Your email</label>
          <input
            type="text"
            id="mail"
            name="email"
            placeholder="Your email"
            required
            class="w-full text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline bg-green-100"
          />
          <label for="lname" class="text-gray-200 pt-3">Subject</label>
          <textarea
            type="textarea"
            id="content"
            name="message"
            placeholder="Write Something"
            required
            class="w-full text-gray-900 mt-2 p-3 rounded-lg focus:outline-none focus:shadow-outline bg-green-100"
          />
          <input
            type="submit"
            value="Submit"
            class="p-2 px-8 mt-5 bg-green-500 border border-none rounded cursor-pointer"
          />
        </div>
      </form>
    </div>
  </div>
</main>

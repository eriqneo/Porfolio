<script>
  export let title;
  export let description;
  export let mode;
</script>

<section>
  <div class="w-80 md:w-80 lg:w-80  rounded overflow-hidden bg-gray-900">
    <div class="pl-2 pt-2">
      <h3 class="font-bold text-green-400 pb-2 underline text-xl">
        {title}
      </h3>
      <p class="text-sm text-gray-400 pt-2 pb-4">{description}</p>
    </div>
    <div class="text-center">
      <span
        class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
        >{mode}</span
      >
    </div>
  </div>
</section>

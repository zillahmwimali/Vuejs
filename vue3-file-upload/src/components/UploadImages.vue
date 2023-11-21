<template>
  <div class="container mx-auto rounded-xl p-4 m-4">
    <p class="text-3xl font-bold mb-5">Vue File upload integration</p>
  </div>

  <div class="flex min-h-1/2 items-center justify-center font-sans p-4">
    <section
      class="mx-auto cursor-pointer flex w-full max-w-lg flex-col items-center rounded-xl border-2 border-dashed border-gray-200 bg-white p-6 text-center"
      @click="openFileInput"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-10 w-10 text-blue-500"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        stroke-width="2"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12"
        />
      </svg>

      <h2 class="mt-4 text-xl font-medium text-gray-700 tracking-wide">Upload image</h2>

      <p class="mt-2 text-gray-500 tracking-wide">
        Upload or drag & drop your file JPEG, PNG or JPG
      </p>

      <input id="dropzone-file" ref="inputFile" type="file" class="hidden" multiple accept="image/*" />
    </section>
  </div>
  <div
    class="flex min-h-1/2 items-center justify-start font-sans p-4 container preview bg-gray-200"
  >
    <h1>hey</h1>
  </div>
</template>

<script type="module">
export default {
    
}





</script>

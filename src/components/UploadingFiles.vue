<template>
  <div class="uploading-section bg-white p-2 h-full">
    <h3 class="text-lg font-semibold mb-4">Attachment Task</h3>

    <div
      class="drag-drop-area flex items-center justify-center border border-dashed border-indigo-500 rounded-lg px-10 py-28 mb-6"
    >
      <div class="flex flex-col items-center">
        <span class="material-symbols-outlined h-12 w-12 text-gray-400">
          upload
        </span>
        <p class="text-gray-500">
          Drag & drop your files here or
          <label for="file-upload" class="text-black cursor-pointer underline"
            >Choose file</label
          >
          <input id="file-upload" type="file" class="hidden" />
        </p>
      </div>
    </div>

    <h4 class="text-lg font-semibold mb-4">Uploading Files</h4>
    <div class="m-2">
      <div class="uploading-file flex flex-col mb-6">
        <div class="flex mb-2">
          <img
            src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg"
            class="h-4 w-4 text-gray-500 mr-2"
          />

          <span class="mr-auto text-sm">hifi-v2.fig</span>

          <span
            class="material-symbols-outlined h-6 w-6 text-indigo-500 text-sm"
          >
            check
          </span>
        </div>

        <div class="w-full h-2 bg-indigo-500 rounded-full">
          <div
            class="h-full bg-indigo-600 rounded-full"
            style="width: 100%"
          ></div>
        </div>
        <div class="flex mt-2 font-semibold">
          <span class="text-xs text-gray-500">6MB</span>
          <span class="mr-auto px-1 text-xs text-gray-500">Completed</span>
          <span class="text-xs text-gray-500">100%</span>
        </div>
      </div>

      <div class="flex mb-6">
        <img
          src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg"
          class="h-4 w-4 text-gray-500 mr-2"
        />

        <span class="mr-auto text-sm">wireframe-v2.fig</span>

        <span class="material-symbols-outlined h-6 w-6 text-red-500 text-sm">
          delete
        </span>
      </div>

      <div class="flex mb-4">
        <img
          src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/photoshop/photoshop-original.svg"
          class="h-4 w-4 mr-2"
        />

        <span class="mr-auto text-sm">branding.psd</span>

        <span class="material-symbols-outlined h-6 w-6 text-red-500 text-sm">
          delete
        </span>
      </div>
    </div>
  </div>
</template>

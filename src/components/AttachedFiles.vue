<template>
  <div class="attachment-container pb-5 px-10 bg-white">

    <div class="flex items-center justify-between mb-4">
      <div class="flex items-center gap-2">
        <h3 class="text-xl font-semibold">Attachment</h3>
        <span class="text-gray-400 font-bold">2</span>
      </div>

      <button class="flex item-center text-indigo-700 font-semibold gap-2">
        Download All
        <span class="material-symbols-outlined font-thin text-base">
          download
        </span>
      </button>
    </div>


    <div class="attachment-files flex pt-2 gap-8">

      <div class="flex items-center justify-between mb-2">
        <div class="flex space-x-2">
          <span class="material-symbols-outlined h-6 w-6 text-red-700">
            picture_as_pdf </span>
          <div class="flex flex-col">
            <span class="font-semibold">Sample-brief.pdf</span>
            <span class="text-gray-500 text-sm">563.42 KB</span>
          </div>
        </div>
      </div>
  
      <div class="flex items-center justify-between mb-2">
        <div class="flex space-x-2">
          <span class="material-symbols-outlined h-6 w-6 text-green-700">
            border_all </span>
          <div class="flex flex-col">
            <span class="font-semibold">spreadsheat-d...</span>
            <span class="text-gray-500 text-sm">563.42 KB</span>
          </div>
        </div>
      </div>

      <div class="flex items-center justify-between mb-2">
        <div class="flex space-x-2">
          <span class="material-symbols-outlined h-6 w-6 text-green-700">
            border_all </span>
          <div class="flex flex-col">
            <span class="font-semibold">spreadsheat-d...</span>
            <span class="text-gray-500 text-sm">563.42 KB</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


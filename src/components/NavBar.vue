<template>
  <div class="navbar bg-white shadow-lg pl-4 py-3 flex items-center">
    <div class="logo">
      <img
        src="https://pics.craiyon.com/2023-09-29/bf0e8522935d4a468ff4a474f536d5cd.webp"
        alt="UnifiedHR"
        class="h-12 w-32 rounded"
      />
    </div>

    <div class="flex text-lg space-x-2 ml-28 p-2">
      <span class="material-symbols-outlined text-gray-500"> home </span>
      <span class="text-gray-500">Home</span>
      <span class="material-symbols-outlined text-gray-400 text-base">
        arrow_forward_ios
      </span>
      <span class="text-gray-500">Job</span>
      <span class="material-symbols-outlined text-gray-400 text-base">
        arrow_forward_ios
      </span>
      <span class="text-black font-semibold">Job Detail</span>
    </div>

    <div class="buttons flex items-center space-x-6 ml-auto">
      <button class="share-button flex items-center">
        <div class="flex items-center">
          <span class="pb-0.5 pr-1 text-base text-gray-500">Share</span>
          <span class="material-symbols-outlined text-base text-gray-500">
            share
          </span>
        </div>
      </button>

      <button class="bookmark-button">
        <span class="material-symbols-outlined text-gray-500 text-base">
          star
        </span>
      </button>

      <button class="more-options-button">
        <span class="material-symbols-outlined text-gray-500 text-base">
          more_horiz
        </span>
      </button>
    </div>
  </div>
</template>

<template>
  <div class="activity-log-container bg-white py-6 px-10">
  
    <div class="flex items-center mb-4">
      <h3 class="text-xl font-semibold mr-auto">Activity Log</h3>
      <div class="flex items-center space-x-2">
        
        <span class="material-symbols-outlined h-5 w-5 text-base text-gray-500">
          search
        </span>
       
        <span class="material-symbols-outlined h-4 w-4 text-base text-gray-500">
          filter_list
        </span>
      </div>
    </div>

    <div class="notification-list">
      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="mr-auto text-gray-500">
          <span class="text-black font-semibold">John Smith</span> created this
          task
        </p>
        <p class="text-gray-500">Mar 20, 3:58 PM</p>
      </div>

      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="mr-auto text-gray-500">
          <span class="text-black font-semibold">John Smith</span> set Type to
          &nbsp;
          <span class="text-orange-500 font-semibold text-sm">Website</span>
        </p>
        <p class="text-gray-500">Mar 21, 1:27 PM</p>
      </div>

      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="mr-auto text-gray-500">
          <span class="text-indigo-700 font-semibold">You</span> downloaded file
          &nbsp;
          <span class="text-black font-semibold">sample-brief.pdf</span>
        </p>
        <p class="text-gray-500">Mar 21, 2:30 PM</p>
      </div>

      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="mr-auto text-gray-500">
          <span class="text-black font-semibold">John Smith</span> set due date
          to &nbsp;<span class="text-black font-semibold">Apr 25, 2024</span>
        </p>
        <p class="text-gray-500">Mar 20, 3:58 PM</p>
      </div>

      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="flex mr-auto text-gray-500">
          <span class="text-indigo-700 font-semibold">You </span> &nbsp;uploaded
          file&nbsp;
          <span class="flex text-black font-semibold">
            <img
              src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg"
              class="h-4 w-4 ml-2 mr-1"
              style="transform: translate(0%, 25%)"
            />
            wireframe-v2.fig
          </span>
        </p>
        <p class="text-gray-500">Apr 01, 2:30 PM</p>
      </div>

      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="flex mr-auto text-gray-500">
          <span class="text-indigo-700 font-semibold">You</span>&nbsp;uploaded
          file&nbsp;
          <span class="flex text-black font-semibold">
            <img
              src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/photoshop/photoshop-original.svg"
              class="h-4 w-4 ml-2 mr-1"
              style="transform: translate(0%, 25%)"
            />

            branding.psd
          </span>
        </p>
        <p class="text-gray-500">Apr 01, 2:34 PM</p>
      </div>
      <div class="notification flex items-center justify-between mb-2">
        <p class="mr-2 text-lg">&bullet;</p>
        <p class="flex mr-auto text-gray-500">
          <span class="text-indigo-700 font-semibold">You</span>&nbsp;uploaded
          file&nbsp;
          <span class="flex text-black font-semibold">
            <img
              src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg"
              class="h-4 w-4 ml-2 mr-1"
              style="transform: translate(0%, 25%)"
            />
            hifi-v2.fig
          </span>
        </p>
        <p class="text-gray-500">Apr 01, 2:37 PM</p>
      </div>
    </div>
  </div>
</template>

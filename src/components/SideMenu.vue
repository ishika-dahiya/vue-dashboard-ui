<template>
  <div class="side-menu">

    <div class="flex items-center px-4 py-6 mb-4">
      <span class="h-8 w-8 rounded mr-2 bg-indigo-500 pt-1 text-center text-white">MF</span>
      <span class="text-sm font-semibold">March Fonda</span>
      <span class="material-symbols-outlined text-gray-600 ml-auto">
        keyboard_arrow_down
      </span>
    </div>


    <div class="flex flex-col justify-between menu-options mb-5">

      <div class="flex items-center p-4 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> search </span>
        <span class="text-sm">Search</span>
      </div>
      <div class="flex items-center px-4 py-2  cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> home </span>
        <span class="text-sm">Home</span>
      </div>
      <div class="flex items-center px-4 py-2 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> group </span>
        <span class="text-sm">People</span>
        <span class="material-symbols-outlined text-gray-600 ml-auto">
          keyboard_arrow_down
        </span>
      </div>
      <div
        class="flex items-center px-4 py-2 cursor-pointer text-indigo-700"
      >
        <span class="material-symbols-outlined text-xl mr-2">
          description
        </span>
        <span class="text-sm">Jobs</span>
      </div>
      <div class="flex items-center px-4 py-2 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> analytics </span>
        <span class="text-sm">Analytics</span>
      </div>
      <div class="flex items-center px-4 py-2 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> difference </span>
        <span class="text-sm">Compliance</span>
      </div>
      <div class="flex items-center px-4 py-2 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> payments </span>
        <span class="text-sm">Payment</span>
      </div>
      <div class="flex items-center px-4 py-2 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> demography </span>
        <span class="text-sm">Immigrations</span>
      </div>
      <div class="flex items-center px-4 py-2 cursor-pointer">
        <span class="material-symbols-outlined text-xl mr-2"> groups </span>
        <span class="text-sm">Team Settings</span>
      </div>

      <div class="mt-auto">
        <div class="flex items-center px-4 py-2 cursor-pointer">
          <span class="material-symbols-outlined text-xl mr-2"> settings </span>
          <span class="text-sm">Settings</span>
        </div>
        <div class="flex items-center px-4 py-2 cursor-pointer">
          <span class="material-symbols-outlined text-xl mr-2">
            support_agent
          </span>
          <span class="text-sm">Customer Service</span>
        </div>
        <div class="flex items-center px-4 py-2 cursor-pointer">
          <span class="material-symbols-outlined text-xl mr-2"> logout </span>
          <span class="text-sm">Logout</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.side-menu {
  width: 240px;
  height: 100%;
  background-color: #ffffff;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.side-menu .menu-options {
  overflow-y: auto;
  height: calc(100% - 96px);
}
</style>

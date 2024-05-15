<template>
  <div class="home-view-container flex flex-col h-screen">
    <main class="flex-1 overflow-y-auto">
      <div>
        <NavBar />
        <div class="flex flex-col lg:flex-row">
          <div class="lg:w-1/8">
            <SideMenu />
          </div>
          <div class="lg:w-3/5">
            <JobDescription />
            <AttachedFiles />
            <ActivityLog />
          </div>
          <div class="lg:w-1/4">
            <UploadingFiles />
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import SideMenu from "@/components/SideMenu.vue";
import JobDescription from "@/components/JobDescription.vue";
import AttachedFiles from "@/components/AttachedFiles.vue";
import ActivityLog from "@/components/ActivityLog.vue";
import UploadingFiles from "@/components/UploadingFiles.vue";

export default {
  name: "HomeView",
  components: {
    NavBar,
    SideMenu,
    JobDescription,
    AttachedFiles,
    ActivityLog,
    UploadingFiles,
  },
};
</script>

<style scoped>
.home-view-container {
  min-height: 100vh;
  background-color: rgb(255, 255, 255);
}

main {
  flex: 1;
  overflow-y: auto; 
  padding: 10px 160px; 
}
</style>

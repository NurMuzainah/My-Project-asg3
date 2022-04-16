<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <h1 class="text-2xl font-bold underline">
          Profile
        </h1><br>
     <div class="bg-white shadow overflow-hidden sm:rounded-lg">
      <img class="inline-block rounded-full w-32 border-2 border-gray-300" src="./assets/photo.jpeg"><br><br>
       <div class="border-t border-gray-200">
          <dl>
            <div class="bg-blue-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
              <dt class="text-sm font-medium underline text-gray-500">Personal Statement</dt><br>
              <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">I am interested to experience new things in order to improve and gain more knowledge</dd>
            </div>
            <div class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
              <dt class="text-sm font-medium underline text-gray-500">Full name</dt><br>
              <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">Nur Muzainah binti Sanib Bahar</dd>
            </div>
            <div class="bg-blue-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
              <dt class="text-sm font-medium underline text-gray-500">Email address</dt><br>
              <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">20FTT1814@student.pb.edu.bn</dd>
            </div>
            <div class="bg-gray-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
              <dt class="text-sm font-medium underline text-gray-500">Hobbies</dt><br>
              <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">Playing badminton and coding</dd>
            </div>
            
            
          </dl>
        </div>     
    </div>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

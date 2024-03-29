<script>
</script>

<template>
  <section class="mt-8">
<section>
    <div
      class="flex flex-col md:flex-row items-center justify-center md:justify-start space-y-8 md:space-x-8"
    >
      <!-- Text content -->
      <div class="w-full md:w-1/2 text-center">
        <h1 ref="text" class="text-3xl md:text-4xl font-bold mb-4">Hi! I am Ems Mary Tampus</h1>
        <p class="text-lg font-bold">A BSIT student at Cordova Public College.</p>
        <p class="text-lg font-semibold">and Web Developer</p>
      </div>
      <!-- Big image -->
      <div class="w-full md:w-1/2 flex justify-center">
        <img
          src="/ems.jpg"
          alt="Portfolio Image"
          class="w-64 h-64 rounded-full shadow-lg"
        />
      </div>
    </div>
</section>
    <section>
      <div class="container mx-auto mt-8">
        <h1 class="text-2xl font-bold mb-4 text-center text-gray-800">
          Projects
        </h1>
        <h2 class="text-xl font-bold text-center mb-4 text-gray-600">
          Here are some of my projects
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
          <!-- Card 1 -->
          <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img
              src="/chat.png"
              alt="Project 1"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h2 class="text-xl font-bold mb-2">Chatify using laravel library</h2>
              <p class="text-gray-600">Description of project 1 goes here.</p>
            </div>
          </div>
          <!-- Card 2 -->
          <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img
              src="/spotify.png"
              alt="Project 2"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h2 class="text-xl font-bold mb-2">Spotify API using Node js</h2>
              <p class="text-gray-600">Description of project 2 goes here.</p>
            </div>
          </div>
          <!-- Card 3 -->
          <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img
              src="/uns.png"
              alt="Project 3"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h2 class="text-xl font-bold mb-2">Unsplash Api - Javascript</h2>
              <p class="text-gray-600">Description of project 3 goes here.</p>
            </div>
          </div>
          <!-- Card 4 -->
          <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img
              src="/image.png"
              alt="Project 4"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h2 class="text-xl font-bold mb-2">TODO App using Vue js</h2>
              <p class="text-gray-600">Description of project 4 goes here.</p>
            </div>
          </div>
          <!-- Card 5 -->
          <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img
              src="/curd.png"
              alt="Project 5"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h2 class="text-xl font-bold mb-2">Simple Crud using Vue js</h2>
              <p class="text-gray-600">Description of project 5 goes here.</p>
            </div>
          </div>
          <!-- Card 6 -->
          <div class="bg-white rounded-lg shadow-md overflow-hidden">
            <img
              src="/port.png"
              alt="Project 6"
              class="w-full h-48 object-cover"
            />
            <div class="p-4">
              <h2 class="text-xl font-bold mb-2">Portfolio Website - Vuejs</h2>
              <p class="text-gray-600">Description of project 6 goes here.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="bg-white py-12">
      <div class="max-w-4xl mx-auto px-4">
        <h1 class="text-3xl font-bold text-center text-gray-800 mb-6">
          Contacts
        </h1>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
          <!-- Contact Information -->
          <div class="bg-white p-6 rounded-lg shadow-md">
            <h2 class="text-xl font-semibold text-gray-800 mb-4">
              Contact Information
            </h2>
            <p class="text-gray-700 mb-2">
              <i class="fas fa-envelope mr-2"></i>emsmarytampus8@gmail.com
            </p>
            <p class="text-gray-700 mb-2">
              <i class="fas fa-phone mr-2"></i>+1234567890
            </p>
            <p class="text-gray-700 mb-2">
              <i class="fas fa-map-marker-alt mr-2"></i>Gabi, Cordova, Cebu
            </p>
          </div>

          <!-- Contact Form -->
          <div class="bg-white p-6 rounded-lg shadow-md">
            <h2 class="text-xl font-semibold text-gray-800 mb-4">
              Send a Message
            </h2>
            <form>
              <div class="mb-4">
                <label
                  for="name"
                  class="block text-sm font-medium text-gray-700"
                  >Name</label
                >
                <input
                  type="text"
                  id="name"
                  name="name"
                  class="mt-1 p-2 w-full border border-gray-300 rounded-md focus:outline-none focus:ring-indigo-500 focus:border-indigo-500"
                />
              </div>
              <div class="mb-4">
                <label
                  for="email"
                  class="block text-sm font-medium text-gray-700"
                  >Email</label
                >
                <input
                  type="email"
                  id="email"
                  name="email"
                  class="mt-1 p-2 w-full border border-gray-300 rounded-md focus:outline-none focus:ring-indigo-500 focus:border-indigo-500"
                />
              </div>
              <div class="mb-4">
                <label
                  for="message"
                  class="block text-sm font-medium text-gray-700"
                  >Message</label
                >
                <textarea
                  id="message"
                  name="message"
                  rows="4"
                  class="mt-1 p-2 w-full border border-gray-300 rounded-md focus:outline-none focus:ring-indigo-500 focus:border-indigo-500"
                ></textarea>
              </div>
              <button
                type="submit"
                class="inline-block px-6 py-3 bg-indigo-600 text-white rounded-md hover:bg-indigo-700 focus:outline-none focus:bg-indigo-700"
              >
                Send Message
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<style></style>

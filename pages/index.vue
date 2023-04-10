<template>
  <div
    class="min-h-screen bg-gray-50 flex flex-col justify-center py-12 sm:px-6 lg:px-8"
  >
    <div class="sm:mx-auto sm:w-full sm:max-w-md">
      <img class="mx-auto w-24 w-auto" src="~/assets/logo.svg" alt="Workflow" />
      <p
        class="mt-6 text-center text-base leading-5 text-gray-500 max-w-xs mx-auto leading-snug"
      >
        Welcome back, enter your credentials below to login
      </p>
    </div>

    <div class="mt-8 sm:mx-auto sm:w-full sm:max-w-md px-4 sm:px-0">
      <div class="bg-white py-8 px-4 shadow sm:rounded-lg sm:px-10">
        <form>
          <div class="mb-4">
            <label
              for="email"
              class="block text-sm font-medium leading-5 text-gray-700"
            >
              Email
            </label>

            <div class="mt-1 rounded-md shadow-sm">
              <input
                id="email"
                type="email"
                required
                placeholder="******************"
                class="appearance-none block w-full px-3 py-2 border border-gray-300 rounded-md placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-[#2d0091] focus:border-blue-300 transition duration-150 ease-in-out sm:text-sm sm:leading-5"
              />
            </div>
          </div>
          <div>
            <label
              for="password"
              class="block text-sm font-medium leading-5 text-gray-700"
            >
              Password
            </label>

            <div class="mt-1 rounded-md shadow-sm">
              <input
                id="password"
                type="password"
                required
                placeholder="******************"
                class="appearance-none block w-full px-3 py-2 border border-gray-300 rounded-md placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-[#2d0091] focus:border-blue-300 transition duration-150 ease-in-out sm:text-sm sm:leading-5"
              />
            </div>
          </div>

          <div class="mt-6">
            <span class="block w-full rounded-md shadow-sm">
              <button
                type="submit"
                class="rounded-full tracking-wider bg-[#2d0091] text-white font-bold text-center py-3 px-8 text-sm uppercase transition transform hover:scale-105 focus:outline-none w-full"
              >
                Login
              </button>
            </span>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script></script>

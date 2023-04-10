<template>
  <div
    class="min-h-screen bg-gray-900 flex flex-col justify-center py-12 sm:px-6 lg:px-8"
  >
    <div class="sm:mx-auto sm:w-full sm:max-w-md">
      <img class="mx-auto w-24 w-auto" src="~/assets/logo.svg" alt="Workflow" />
      <p
        class="mt-6 text-center text-base leading-5 text-gray-300 max-w-xs mx-auto leading-snug"
      >
        Welcome back, enter your credentials below to login
      </p>
    </div>

    <div class="mt-8 sm:mx-auto sm:w-full sm:max-w-md px-4 sm:px-0">
      <div class="bg-gray-800 py-8 px-4 shadow sm:rounded-lg sm:px-10">
        <form>
          <div class="mb-4">
            <label
              for="email"
              class="font-medium text-gray-700 text-white text-sm"
            >
              Email
            </label>

            <div class="mt-1 rounded-md shadow-sm">
              <input
                id="email"
                type="email"
                required
                placeholder="******************"
                class="appearance-none block w-full px-3 py-2 rounded-md placeholder-gray-300 focus:outline-none focus:ring-teal-600 focus:ring-teal-500 focus:border-teal-500 transition duration-150 ease-in-out sm:text-sm sm:leading-5 bg-gray-600 text-white"
              />
            </div>
          </div>
          <div>
            <label
              for="password"
              class="font-medium text-gray-700 text-white text-sm"
            >
              Password
            </label>

            <div class="mt-1 rounded-md shadow-sm">
              <input
                id="password"
                type="password"
                required
                placeholder="******************"
                class="appearance-none block w-full px-3 py-2 rounded-md placeholder-gray-300 focus:outline-none focus:ring-teal-600 focus:ring-teal-500 focus:border-teal-500 transition duration-150 ease-in-out sm:text-sm sm:leading-5 bg-gray-600 text-white"
              />
            </div>
          </div>

          <div class="mt-6">
            <span class="block w-full rounded-md shadow-sm">
              <button
                type="submit"
                class="text-white py-3 px-6 uppercase font-bold rounded-full text-sm text-center bg-teal-600 w-full hover:bg-teal-500"
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

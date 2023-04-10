<template>
  <div
    class="fixed inset-0 md:flex flex-col md:flex-row md:items-center justify-center h-xl h-screen z-50 py-4 md:py-12 overflow-scroll lg:overflow-auto bg-gray-900"
  >
    <div class="z-10 relative mt-8 mx-auto md:m-auto px-4 mb-24 modal">
      <form
        class="max-w-md w-full md:max-w-3xl mx-auto md:flex bg-white bg-gray-800 shadow-md md:pl-0 md:py-0 rounded relative"
      >
        <div
          class="md:w-1/2 bg-[#BDE5E4] rounded-t px-8 py-6 md:rounded-l md:flex md:items-center md:px-8"
        >
          <div>
            <video loop autoplay playsinline muted class="w-48 mx-auto">
              <source src="~assets/badge.mp4" type="video/mp4" />
            </video>

            <p class="mt-6 text-center text-teal-900 text-lg">
              Create an account to make purchases, participate in discussions,
              and track your course progress.
            </p>
          </div>
        </div>
        <div class="p-4 md:w-1/2 md:px-8 md:py-8">
          <div class="mb-1">
            <div>
              <label
                for="email"
                class="block text-sm font-medium leading-5 text-gray-700 text-white"
              >
                Email Address
              </label>

              <div class="mt-1 rounded-md shadow-sm">
                <input
                  ref="email"
                  type="email"
                  placeholder="you@example.com"
                  class="appearance-none block w-full px-3 py-2 rounded-md placeholder-gray-300 focus:outline-none focus:ring-teal-600 focus:ring-teal-500 focus:border-teal-500 transition duration-150 ease-in-out sm:text-sm sm:leading-5 bg-gray-600 text-white"
                />
              </div>
            </div>

            <div class="mt-6">
              <div>
                <label
                  for="username"
                  class="block text-sm font-medium leading-5 text-gray-700 text-white"
                >
                  Username
                </label>

                <div class="mt-1 rounded-md shadow-sm">
                  <input
                    ref="username"
                    type="text"
                    placeholder="Must be 4-20 characters"
                    class="appearance-none block w-full px-3 py-2 rounded-md placeholder-gray-300 focus:outline-none focus:ring-teal-600 focus:ring-teal-500 focus:border-teal-500 transition duration-150 ease-in-out sm:text-sm sm:leading-5 bg-gray-600 text-white"
                  />
                </div>
              </div>

              <div class="mt-6">
                <label
                  for="password"
                  class="block text-sm font-medium leading-5 text-gray-700 text-white"
                >
                  Password
                </label>
                <div class="mt-1 rounded-md shadow-sm">
                  <input
                    ref="password"
                    type="password"
                    placeholder="****************"
                    class="appearance-none block w-full px-3 py-2 rounded-md placeholder-gray-300 focus:outline-none focus:ring-teal-600 focus:ring-teal-500 focus:border-teal-500 transition duration-150 ease-in-out sm:text-sm sm:leading-5 bg-gray-600 text-white"
                  />
                </div>
              </div>
            </div>

            <div class="mt-3">
              <div class="flex items-start">
                <div class="absolute flex items-center h-5">
                  <input
                    id="username-terms"
                    type="checkbox"
                    class="form-checkbox h-4 w-4 text-teal-500 transition duration-150 ease-in-out rounded focus:ring-teal-500 focus:border-gray-300"
                  />
                </div>
                <div class="pl-7 text-sm leading-5">
                  <label
                    for="username-terms"
                    class="font-medium text-gray-700 text-white"
                    >I agree to the
                    <a href="/terms" target="_blank" class="text-teal-500">
                      terms and conditions</a
                    >.</label
                  >
                </div>
              </div>
            </div>
            <div class="flex items-center justify-end mt-4">
              <button
                class="text-white py-3 px-6 uppercase font-bold rounded-full text-sm text-center bg-teal-600 w-full hover:bg-teal-500"
                type="submit"
              >
                Create Account
              </button>
            </div>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

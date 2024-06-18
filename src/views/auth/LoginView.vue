<script setup lang="ts">

</script>
<template>
<div class="bg-no-repeat bg-cover bg-center relative h-full" style="background-image: url('./enjoy/wen.jpeg');">
    <div class="absolute bg-gradient-to-r from-cyan-500 to-blue-500"></div>
<div class="flex min-h-full flex-col justify-center py-12 sm:px-6 lg:px-8">
  <div class="sm:mx-auto sm:w-full sm:max-w-md mb-5">
    
    <h2 class="mt-6 text-center text-4xl font-bold leading-9 tracking-tight text-white">Karibu Enjoy Tourism</h2>
  </div>

  <div class="sm:mx-auto sm:w-full sm:max-w-[480px]">
    <div class="bg-white rounded-lg  px-6 py-12 shadow sm:rounded-lg sm:px-12">
      <form class="space-y-6"  method="POST">
        <div>
          <label for="username" class="block text-sm font-medium leading-6 text-gray-900">Nom d'utilisateur</label>
          <div class="mt-2">
            <input name="username" placeholder="ex:djunga@pascal" type="text" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
          </div>
        </div>

        <div>
          <label for="password" class="block text-sm font-medium leading-6 text-gray-900">Mot de passe</label>
          <div class="mt-2">
            <input name="password" type="password" placeholder="1234" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
          </div>
        </div>

        <div class="flex items-center justify-between">
          <div class="flex items-center">
            <input id="remember-me" name="remember-me" type="checkbox" class="h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600">
            <label for="remember-me" class="ml-3 block text-sm leading-6 text-gray-900">Remember me</label>
          </div>

          <div class="text-sm leading-6">
            <a href="#" class="font-semibold text-indigo-600 hover:text-indigo-500">Forgot password?</a>
          </div>
        </div>

        <div>
          <button type="submit" class="flex w-full justify-center rounded-md bg-gray-800 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">{{ "Se connecter" }}</button>
        </div>
      </form>

      <div>
        <div class="relative mt-10">
          <div class="absolute inset-0 flex items-center" aria-hidden="true">
            <div class="w-full border-t border-gray-200"></div>
          </div>
          <div class="relative flex justify-center text-sm font-medium leading-6">
            <span class="bg-green-600 rounded-lg px-6 text-white">Karibu</span>
          </div>
        </div>

        <div class="mt-6  gap-4">
          <a href="#" class="flex w-full items-center justify-center gap-3 rounded-md bg-white px-3 py-2 text-sm font-semibold text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 hover:bg-gray-50 focus-visible:ring-transparent">
            <svg class="h-5 w-5" viewBox="0 0 24 24" aria-hidden="true">
              <path d="M12.0003 4.75C13.7703 4.75 15.3553 5.36002 16.6053 6.54998L20.0303 3.125C17.9502 1.19 15.2353 0 12.0003 0C7.31028 0 3.25527 2.69 1.28027 6.60998L5.27028 9.70498C6.21525 6.86002 8.87028 4.75 12.0003 4.75Z" fill="#EA4335" />
              <path d="M23.49 12.275C23.49 11.49 23.415 10.73 23.3 10H12V14.51H18.47C18.18 15.99 17.34 17.25 16.08 18.1L19.945 21.1C22.2 19.01 23.49 15.92 23.49 12.275Z" fill="#4285F4" />
              <path d="M5.26498 14.2949C5.02498 13.5699 4.88501 12.7999 4.88501 11.9999C4.88501 11.1999 5.01998 10.4299 5.26498 9.7049L1.275 6.60986C0.46 8.22986 0 10.0599 0 11.9999C0 13.9399 0.46 15.7699 1.28 17.3899L5.26498 14.2949Z" fill="#FBBC05" />
              <path d="M12.0004 24.0001C15.2404 24.0001 17.9654 22.935 19.9454 21.095L16.0804 18.095C15.0054 18.82 13.6204 19.245 12.0004 19.245C8.8704 19.245 6.21537 17.135 5.2654 14.29L1.27539 17.385C3.25539 21.31 7.3104 24.0001 12.0004 24.0001Z" fill="#34A853" />
            </svg>
            <span class="text-sm font-semibold leading-6">S'inscrire</span>
          </a>

         
        </div>
        <img class="mx-auto h-24 w-auto" src="../../../enjoy/logo.png" alt="Your Company">
      </div>
    </div>
<br><br>

  </div>
</div>
 
</div>

<!-- component
<!-- <div class="bg-no-repeat bg-cover bg-center relative" style="background-image: url(https://images.unsplash.com/photo-1579621970563-ebec7560ff3e?ixlib=rb-1.2.1&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=crop&amp;w=1951&amp;q=80);"><div class="absolute bg-gradient-to-b from-green-500 to-green-400 opacity-75 inset-0 z-0"></div>
  <div class="min-h-screen sm:flex sm:flex-row mx-0 justify-center">
      <div class="flex-col flex  self-center p-10 sm:max-w-5xl xl:max-w-2xl  z-10">
        <div class="self-start hidden lg:flex flex-col  text-white">
          <img src="" class="mb-3">
          <h1 class="mb-3 font-bold text-5xl">Hi ? Welcome Back Aji </h1>
          <p class="pr-3">Lorem ipsum is placeholder text commonly used in the graphic, print,
            and publishing industries for previewing layouts and visual mockups</p>
        </div>
      </div>
      <div class="flex justify-center self-center  z-10">
        <div class="p-12 bg-white mx-auto rounded-2xl w-100 ">
            <div class="mb-4">
              <h3 class="font-semibold text-2xl text-gray-800">Sign In </h3>
              <p class="text-gray-500">Please sign in to your account.</p>
            </div>
            <div class="space-y-5">
                        <div class="space-y-2">
                              <label class="text-sm font-medium text-gray-700 tracking-wide">Email</label>
              <input class=" w-full text-base px-4 py-2 border  border-gray-300 rounded-lg focus:outline-none focus:border-green-400" type="" placeholder="mail@gmail.com">
              </div>
                          <div class="space-y-2">
              <label class="mb-5 text-sm font-medium text-gray-700 tracking-wide">
                Password
              </label>
              <input class="w-full content-center text-base px-4 py-2 border  border-gray-300 rounded-lg focus:outline-none focus:border-green-400" type="" placeholder="Enter your password">
            </div>
              <div class="flex items-center justify-between">
              <div class="flex items-center">
                <input id="remember_me" name="remember_me" type="checkbox" class="h-4 w-4 bg-blue-500 focus:ring-blue-400 border-gray-300 rounded">
                <label for="remember_me" class="ml-2 block text-sm text-gray-800">
                  Remember me
                </label>
              </div>
              <div class="text-sm">
                <a href="#" class="text-green-400 hover:text-green-500">
                  Forgot your password?
                </a>
              </div>
            </div>
            <div>
              <button type="submit" class="w-full flex justify-center bg-green-400  hover:bg-green-500 text-gray-100 p-3  rounded-full tracking-wide font-semibold  shadow-lg cursor-pointer transition ease-in duration-500">
                Sign in
              </button>
            </div>
            </div>
            <div class="pt-5 text-center text-gray-400 text-xs">
              <span>
                Copyright © 2021-2022
                <a href="https://codepen.io/uidesignhub" rel="" target="_blank" title="Ajimon" class="text-green hover:text-green-500 ">AJI</a></span>
            </div>
        </div>
      </div>
  </div>
</div> -->
</template>
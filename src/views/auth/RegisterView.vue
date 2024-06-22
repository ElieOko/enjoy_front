<script setup lang="ts">
</script>
<template>
<div class="min-h-screen bg-no-repeat bg-cover bg-center" style="background-image:linear-gradient(rgb(0 0 0 / 60%), rgb(0 0 0 / 60%)), url('./enjoy/wen.jpeg')" >
  
    <div class="flex  min-h-full flex-col justify-center py-12 sm:px-6 lg:px-8">
  <div class="sm:mx-auto sm:w-full sm:max-w-md mb-5">
    
    <h2 class="mt-6 text-center text-4xl font-bold leading-9 tracking-tight text-white">Karibu Enjoy Tourism</h2>
  </div>

  <div class="sm:mx-auto sm:w-full sm:max-w-[480px]">
    <div class="bg-white rounded-lg  px-6 py-12 shadow sm:rounded-lg sm:px-12">
      <form class="space-y-6"  method="POST">
        <div class="grid grid-cols-2 gap-4">
            <div>
          <label for="nom" class="block text-sm font-medium leading-6 text-gray-900">Nom</label>
          <div class="mt-2">
            <input name="nom" placeholder="ex:djunga@pascal" type="text" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
          </div>
        </div>
        <div>
          <label for="prenom" class="block text-sm font-medium leading-6 text-gray-900">Prenom</label>
          <div class="mt-2">
            <input name="prenom" placeholder="ex:djunga@pascal" type="text" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
          </div>
        </div>
        </div>
        <div class="grid grid-cols-2 gap-4">
            <div>
            <label for="genre" class="block text-sm font-medium leading-6 text-gray-900">Genre</label>
            <select id="genre" name="genre" class="mt-2 block w-full rounded-md border-0 py-1.5 pl-3 pr-10 text-gray-900 ring-1 ring-inset ring-gray-300 focus:ring-2 focus:ring-indigo-600 sm:text-sm sm:leading-6">
                <option selected>homme(m)</option>
                <option >femme(f)</option>
            </select>
        </div>

        <div>
        <label for="telephone" class="block text-sm font-medium leading-6 text-gray-900">Téléphone</label>
          <div class="mt-2">
            <input name="telephone" placeholder="ex:+243827824163" type="text" required class="block w-full rounded-md border-0 py-1.5 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6">
          </div>  
        </div>
        </div>
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
        <div>
          <button type="submit" class="flex w-full justify-center rounded-md bg-gray-800 px-3 py-1.5 text-sm font-semibold leading-6 text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">{{ "S'inscrire" }}</button>
        </div>
      </form>

      <div>
        <div class="relative mt-10">
          <div class="absolute inset-0 flex items-center" aria-hidden="true">
            <div class="w-full border-t border-gray-200"></div>
          </div>
          <div class="relative flex justify-center text-sm font-medium leading-6">
            <span class="bg-green-600 rounded-lg px-6 text-white">GBES</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
</template>
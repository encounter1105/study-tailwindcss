<template>
  <!--<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">-->
    <!--<div class="md:flex">-->
      <!--<div class="md:flex-shrink-0">-->
        <!--<img class="h-48 w-full object-cover md:w-48" src="../assets/logo.png" alt="Man looking at item at a store">-->
      <!--</div>-->
      <!--<div class="p-8">-->
        <!--<div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Case study</div>-->
        <!--<a href="#" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Finding customers for your new business</a>-->
        <!--<p class="mt-2 text-gray-500">Getting a new business off the ground is a lot of hard work. Here are five ideas you can use to find your first customers.</p>-->
      <!--</div>-->
    <!--</div>-->
  <!--</div>-->
    <div class="container mx-auto">
        <div class="flex justify-between items-center py-4 bg-blue-900">
            <div class="flex-shrink-0 ml-10 cursor-pointer">
                <i class="fas fa-drafting-compass fa-2x text-orange-500"></i>
                <span class="ml-1 text-3xl text-blue-200 font-semibold">WebCraft</span>
            </div>
            <i class="fas fa-bars fa-2x visible md:invisible mr-10 md:mr-0 text-blue-200 cursor-pointer"></i>
            <ul class="hidden md:flex overflow-x-hidden mr-10 font-semibold">
                <li class="mr-6 p-1 border-b-2 border-orange-500">
                    <a class="text-blue-200 cursor-default" href="#">Home</a>
                </li>
                <li class="mr-6 p-1">
                    <a class="text-white hover:text-blue-300" href="#">Services</a>
                </li>
                <li class="mr-6 p-1">
                    <a class="text-white hover:text-blue-300" href="#">Projects</a>
                </li>
                <li class="mr-6 p-1">
                    <a class="text-white hover:text-blue-300" href="#">Team</a>
                </li>
                <li class="mr-6 p-1">
                    <a class="text-white hover:text-blue-300" href="#">About</a>
                </li>
                <li class="mr-6 p-1">
                    <a class="text-white hover:text-blue-300" href="#">Contacts</a>
                </li>
            </ul>
        </div>

    </div>
</template>

<script>
import "font-awesome/css/font-awesome.css"
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>

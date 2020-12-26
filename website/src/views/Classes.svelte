<script>
import SignupButton from '../components/SignupButton.svelte'

</script>

<div class="text-center text-3xl md:text-4xl lg:text-5xl font-medium mt-16 mb-8 lg:mb-12">Classes</div>

<div class="flex justify-center">
  <div class="px-6 md:px-14 lg:px-24 md:mx-24 lg:mx-40 xl:w-2/3">
    <div class="rounded-lg bg-indigo-50 p-6 lg:p-8 text-gray-600 relative">

      <div class="text-2xl md:text-3xl lg:text-4xl font-medium mb-6 text-black">NACLO</div>
  
      <div>
        January 2 - March 6 (10 classes)
      </div>
      <div>
        Every second Saturday, 5:00 - 6:00 PM
      </div>
      <div>
        For grades 7 to 9
      </div>
      <div>
        Free
      </div>
  
      <div class="mt-4 mb-6 md:mb-0">
  
        Comprehensive preparation for 
        <a href="https://www.nacloweb.org/" class="text-indigo-600 hover:text-indigo-800">NACLO</a> and 
        <a href="https://ioling.org/" class="text-indigo-600 hover:text-indigo-800">IOL</a>. 
        Students will investigate features of world languages, including grammar, phonetics, number systems, and writing systems, 
        along with topics in computational linguistics and analytic reasoning.
      </div>

      <div class="md:absolute md:top-0 md:right-0 md:p-8">
        <SignupButton width=4 height=2/>
      </div>
    </div>
  </div>
  
</div>

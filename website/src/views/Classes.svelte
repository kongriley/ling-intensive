<script>
import SignupButton from '../components/SignupButton.svelte'
import Link from '../components/Link.svelte'
</script>

<div class="text-center text-3xl md:text-4xl lg:text-5xl font-medium mt-16 mb-8 lg:mb-12">Classes</div>

<div class="flex justify-center">
  <div class="px-6 md:px-14 lg:px-24 md:mx-24 lg:mx-40 xl:w-2/3">
    <div class="rounded-lg bg-indigo-50 shadow p-6 lg:p-8 text-gray-600 relative">

      <div class="text-2xl md:text-3xl lg:text-4xl font-medium mb-6 text-black">NACLO</div>
  
      <div>
        January 9 - March 20 (6 classes)
      </div>
      <div>
        Every second Saturday, 5:00 - 6:00 PM PST
      </div>
      <div>
        For grades 7 to 12
      </div>
      <div>
        Free, online
      </div>
  
      <div class="mt-4">
  
        Comprehensive preparation for the
        <Link href="https://www.nacloweb.org/" text="NACLO" /> 
        (North American Computational Linguistics Olympiad) and the
        <Link href="https://ioling.org/" text="IOL" /> 
        (International Linguistics Olympiad). 
        Students will investigate features of world languages, including grammar, phonetics, number systems, and writing systems, 
        along with topics in computational linguistics and analytic reasoning.
      </div>


      <div class="text-lg md:text-xl lg:text-2xl font-medium mt-6 mb-4 text-black">Schedule</div>
      <table class="w-full border-collapse border-gray-600 mb-6 md:mb-0">
        <thead>
          <tr class="text-left font-medium bg-indigo-100">
            <th class="p-2 border border-gray-300">Date</th>
            <th class="p-2 border border-gray-300">Topic</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="p-2 border border-gray-300">January 9</td>
            <td class="p-2 border border-gray-300">TBA</td>
          </tr>
          <tr>
            <td class="p-2 border border-gray-300">January 23</td>
            <td class="p-2 border border-gray-300">TBA</td>
          </tr>
          <tr class="bg-red-200 text-gray-500">
            <td class="p-2 border border-gray-300">January 28</td>
            <td class="p-2 border border-gray-300">NACLO Open Round</td>
          </tr>
          <tr>
            <td class="p-2 border border-gray-300">February 6</td>
            <td class="p-2 border border-gray-300">TBA</td>
          </tr>
          <tr>
            <td class="p-2 border border-gray-300">February 20</td>
            <td class="p-2 border border-gray-300">TBA</td>
          </tr>
          <tr>
            <td class="p-2 border border-gray-300">March 6</td>
            <td class="p-2 border border-gray-300">TBA</td>
          </tr>
          <tr>
            <td class="p-2 border border-gray-300">March 20</td>
            <td class="p-2 border border-gray-300">TBA</td>
          </tr>
        </tbody>
        
      </table>

      
      <div class="flex md:flex-col md:justify-end items-center md:absolute md:top-0 md:right-0 md:p-8">
        <SignupButton width=4 height=2/>
        <div class="ml-2 md:mt-2">
          Closes 1/6
        </div>
      </div>


    </div>
  </div>
  
</div>

<template>
  <div class="min-h-screen flex relative">
    <h1 class="absolute top-0 ml-8 mt-4 text-3xl font-bold text-gray-700">gamefriendly.io</h1>
    <div class="w-1/2 min-h-screen bg-gray-100 flex items-center justify-center left-pane">
      <div class="w-1/2 bg-red flex flex-col justify-center items-center">
        <h1 class="text-5xl text-gray-700 leading-tight font-bold">It's dangerous to game alone.</h1>
        <p class="text-gray-500 mt-8 text-xl">Join Gamefriendly FREE for 15 days and begin playing with friends from all over the world!</p>
        <form class="w-full mt-8 flex flex-col justify-center items-center">
          <div class="mb-4 w-full">
            <input class="appearance-none bg-white rounded-lg shadow py-4 px-3 w-full text-red-300 border-b-2 border-purple-500" placeholder="Username"/>
          </div>
          <div class="mb-4 w-full">
            <input class="appearance-none bg-white rounded-lg shadow py-4 px-3 w-full text-red-300 border-b-2 border-purple-500" placeholder="Password"/>
          </div>
        </form>
        <button class="mt-8 py-3 px-3 bg-purple-400 text-white rounded-full font-bold w-1/3 mx-auto shadow-md border-b-2 border-purple-600">Sign Up</button>
        <p class="my-4 text-gray-500">or</p>
        <div class="flex items-center">
          <p class="text-gray-700 text-xl mr-3">Sign up with</p>
          <svg
          class="h-auto w-24"
            xmlns:dc="http://purl.org/dc/elements/1.1/"
            xmlns:cc="http://creativecommons.org/ns#"
            xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
            xmlns:svg="http://www.w3.org/2000/svg"
            xmlns="http://www.w3.org/2000/svg"
            id="svg3355"
            version="1.1"
            xml:space="preserve"
            width="454.93066"
            height="150.776"
            viewBox="0 0 454.93066 150.776">
            <g
              id="g3363"
              transform="matrix(1.3333333,0,0,-1.3333333,-180.53426,805.80838)">
              <g
                id="g3371"
                transform="translate(468.8057,565.3643)">
                <path
                  d="m 0,0 -13.646,13.645 -25.35,0 0,17.55 -21.451,0 0,-79.94 21.451,0 0,40.947 17.545,0 0,-40.947 21.451,0 L 0,0 Z m -68.241,13.645 -33.146,0 L -115.036,0 l 0,-35.094 13.649,-13.651 33.146,0 0,21.445 -25.35,0 0,19.502 25.35,0 0,21.443 z m -54.594,0 -17.545,0 0,17.55 -21.451,0 0,-66.289 13.649,-13.651 25.347,0 0,21.445 -17.545,0 0,19.502 17.545,0 0,21.443 z m -46.795,17.55 -21.445,0 0,-9.752 21.445,0 0,9.752 z m 0,-17.55 -21.445,0 0,-62.389 21.445,0 0,62.389 z m -29.244,0 -21.447,0 0,-40.945 -7.797,0 0,40.945 -21.448,0 0,-40.945 -7.796,0 0,40.945 -21.451,0 0,-62.39 66.293,0 13.646,13.651 0,48.739 z m -87.738,0 -17.546,0 0,17.55 -21.447,0 0,-66.289 13.648,-13.651 25.345,0 0,21.445 -17.546,0 0,19.502 17.546,0 0,21.443 z M 7.793,3.9 l 0,-58.491 -29.244,-19.499 -19.496,0 0,9.752 -13.648,-9.752 -17.545,0 0,9.752 -9.746,-9.752 -31.197,0 -9.752,9.752 -1.952,-9.752 -27.292,0 -11.161,9.752 -0.625,-9.752 -30.935,0 -1.094,9.752 -8.374,-9.752 -47.25,0 -9.75,3.9 0,-3.9 -25.344,0 -29.247,17.552 -17.546,17.539 0,77.991 37.047,0 17.545,-17.549 79.939,0 0,17.549 66.29,0 0,-17.549 17.548,0 0,-9.746 9.752,9.746 19.493,0 17.55,17.549 37.044,0 0,-17.549 21.448,0 L 7.793,3.9 Z"
                  style="fill:#6441a5;fill-opacity:1;fill-rule:evenodd;stroke:none"
                  id="path3373" />
              </g>
            </g>
          </svg>
        </div>
        <p class="absolute bottom-0 mb-12">Already have an account?</p>
      </div>
    </div>
    <div class="w-1/2 min-h-screen bg-purple-400 flex items-center justify-center right-pane">
      <img class="w-full h-auto svg-hero" src="https://assets-ouch.icons8.com/preview/287/908e55fb-d72d-41b4-8e60-d81adbbd8d0e.png"/>
    </div>
  </div>
</template>

<script>
import Woman from '~/assets/Woman.svg'
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
    Woman
  }
}
</script>

<style>
.right-pane {
background-color: #b794f4;
background-image: url("data:image/svg+xml,%3Csvg width='180' height='180' viewBox='0 0 180 180' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M81.28 88H68.413l19.298 19.298L81.28 88zm2.107 0h13.226L90 107.838 83.387 88zm15.334 0h12.866l-19.298 19.298L98.72 88zm-32.927-2.207L73.586 78h32.827l.5.5 7.294 7.293L115.414 87l-24.707 24.707-.707.707L64.586 87l1.207-1.207zm2.62.207L74 80.414 79.586 86H68.414zm16 0L90 80.414 95.586 86H84.414zm16 0L106 80.414 111.586 86h-11.172zm-8-6h11.173L98 85.586 92.414 80zM82 85.586L87.586 80H76.414L82 85.586zM17.414 0L.707 16.707 0 17.414V0h17.414zM4.28 0L0 12.838V0h4.28zm10.306 0L2.288 12.298 6.388 0h8.198zM180 17.414L162.586 0H180v17.414zM165.414 0l12.298 12.298L173.612 0h-8.198zM180 12.838L175.72 0H180v12.838zM0 163h16.413l.5.5 7.294 7.293L25.414 172l-8 8H0v-17zm0 10h6.613l-2.334 7H0v-7zm14.586 7l7-7H8.72l-2.333 7h8.2zM0 165.414L5.586 171H0v-5.586zM10.414 171L16 165.414 21.586 171H10.414zm-8-6h11.172L8 170.586 2.414 165zM180 163h-16.413l-7.794 7.793-1.207 1.207 8 8H180v-17zm-14.586 17l-7-7h12.865l2.333 7h-8.2zM180 173h-6.613l2.334 7H180v-7zm-21.586-2l5.586-5.586 5.586 5.586h-11.172zM180 165.414L174.414 171H180v-5.586zm-8 5.172l5.586-5.586h-11.172l5.586 5.586zM152.933 25.653l1.414 1.414-33.94 33.942-1.416-1.416 33.943-33.94zm1.414 127.28l-1.414 1.414-33.942-33.94 1.416-1.416 33.94 33.943zm-127.28 1.414l-1.414-1.414 33.94-33.942 1.416 1.416-33.943 33.94zm-1.414-127.28l1.414-1.414 33.942 33.94-1.416 1.416-33.94-33.943zM0 85c2.21 0 4 1.79 4 4s-1.79 4-4 4v-8zm180 0c-2.21 0-4 1.79-4 4s1.79 4 4 4v-8zM94 0c0 2.21-1.79 4-4 4s-4-1.79-4-4h8zm0 180c0-2.21-1.79-4-4-4s-4 1.79-4 4h8z' fill='%23ffffff' fill-opacity='0.12' fill-rule='evenodd'/%3E%3C/svg%3E");
}
</style>
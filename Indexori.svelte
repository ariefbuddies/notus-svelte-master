<script>
  import { Link } from "svelte-routing";

  // core components
  import IndexNavbar from "components/Navbars/IndexNavbar.svelte";
  import Footer from "components/Footers/Footer.svelte";

  const patternVue = "/assets/img/pattern_svelte.png";
  const componentBtn = "/assets/img/component-btn.png";
  const componentProfileCard = "/assets/img/component-profile-card.png";
  const componentInfoCard = "/assets/img/component-info-card.png";
  const componentInfo2 = "/assets/img/component-info-2.png";
  const componentMenu = "/assets/img/component-menu.png";
  const componentBtnPink = "/assets/img/component-btn-pink.png";
  const documentation = "/assets/img/documentation.png";
  const login = "/assets/img/login.jpg";
  const profile = "/assets/img/profile.jpg";
  const landing = "/assets/img/landing.jpg";
  export let location;
</script>

<IndexNavbar />
<section class="header relative pt-16 items-center flex h-screen max-h-860-px">
  <div class="container mx-auto items-center flex flex-wrap">
    <div class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4">
      <div class="pt-32 sm:pt-0">
        <h2 class="font-semibold text-4xl text-gray-700">
          AriefB Svelte
        </h2>
        <p class="mt-4 text-lg leading-relaxed text-gray-600">
          Notus Svelte is Free and Open Source. It does not change or
          add any CSS to the already one from
          <a
            href="https://tailwindcss.com/?ref=creativetim"
            class="text-gray-700"
            target="_blank"
          >
            Tailwind CSS
          </a>
          . It features multiple HTML elements and it comes with dynamic
          components for ReactJS, Vue and Angular.
        </p>
        <div class="mt-12">
          <a
            href="https://www.creative-tim.com/learning-lab/tailwind/svelte/overview/notus?ref=ns-index"
            target="_blank"
            class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-red-500 active:bg-red-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
          >
            Sewa Motor
          </a>
          <a
            href="https://github.com/creativetimofficial/notus-svelte?ref=ns-index"
            class="github-star ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-gray-800 active:bg-gray-700 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
            target="_blank"
          >
            Rental Mobil
          </a>
        </div>
      </div>
    </div>
  </div>

  <img
    class="absolute top-0 b-auto right-0 pt-16 sm:w-6/12 -mt-48 sm:mt-0 w-10/12 max-h-860-px"
    src="{patternVue}"
    alt="..."
  />
</section>

<section class="mt-48 md:mt-40 pb-40 relative bg-gray-200">
  <div
    class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
    style="transform: translateZ(0);"
  >
    <svg
      class="absolute bottom-0 overflow-hidden"
      xmlns="http://www.w3.org/2000/svg"
      preserveAspectRatio="none"
      version="1.1"
      viewBox="0 0 2560 100"
      x="0"
      y="0"
    >
      <polygon
        class="text-gray-200 fill-current"
        points="2560 0 2560 100 0 100"
      ></polygon>
    </svg>
  </div>
  <div class="container mx-auto">
    <div class="flex flex-wrap items-center">
      <div
        class="w-10/12 md:w-6/12 lg:w-4/12 px-12 md:px-4 mr-auto ml-auto -mt-32"
      >
        <div
          class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-red-500"
        >
          <img
            alt="..."
            src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=700&q=80"
            class="w-full align-middle rounded-t-lg"
          />
          <blockquote class="relative p-8 mb-4">
            <svg
              preserveAspectRatio="none"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 583 95"
              class="absolute left-0 w-full block h-95-px -top-94-px"
            >
              <polygon
                points="-30,95 583,95 583,65"
                class="text-red-500 fill-current"
              ></polygon>
            </svg>
            <h4 class="text-xl font-bold text-white">
              Great for your awesome project
            </h4>
            <p class="text-md font-light mt-2 text-white">
              Putting together a page has never been easier than matching
              together pre-made components. From landing pages presentation to
              login areas, you can easily customise and built your pages.
            </p>
          </blockquote>
        </div>
      </div>

      <div class="w-full md:w-6/12 px-4">
        <div class="flex flex-wrap">
          <div class="w-full md:w-6/12 px-4">
            <div class="relative flex flex-col mt-4">
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                >
                  <i class="fas fa-sitemap"></i>
                </div>
                <h6 class="text-xl mb-1 font-semibold">
                  Sewa Motor
                </h6>
                <p class="mb-4 text-gray-600">
                  Notus Svelte comes with a huge number of Fully Coded CSS
                  components.
                </p>
              </div>
            </div>
            <div class="relative flex flex-col min-w-0">
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                >
                  <i class="fas fa-drafting-compass"></i>
                </div>
                <h6 class="text-xl mb-1 font-semibold">
                  Rental Mobil
                </h6>
                <p class="mb-4 text-gray-600">
                  We also feature many dynamic components for React, NextJS, Vue
                  and Angular.
                </p>
              </div>
            </div>
          </div>
          <div class="w-full md:w-6/12 px-4">
            <div class="relative flex flex-col min-w-0 mt-4">
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                >
                  <i class="fas fa-newspaper"></i>
                </div>
                <h6 class="text-xl mb-1 font-semibold">SEPEDA</h6>
                <p class="mb-4 text-gray-600">
                  This extension also comes with 3 sample pages. They are fully
                  coded so you can start working instantly.
                </p>
              </div>
            </div>
            <div class="relative flex flex-col min-w-0">
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                >
                  <i class="fas fa-file-alt"></i>
                </div>
                <h6 class="text-xl mb-1 font-semibold">
                  Penginapan
                </h6>
                <p class="mb-4 text-gray-600">
                  Built by developers for developers. You will love how easy is
                  to to work with Notus Svelte.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container mx-auto overflow-hidden pb-20">
  

    <div class="flex flex-wrap items-center pt-32">
      <div class="w-full md:w-6/12 px-4 mr-auto ml-auto mt-32">
        <div class="justify-center flex flex-wrap relative">
          <div class="my-4 w-full lg:w-6/12 px-4">
            <a
              href="https://www.creative-tim.com/learning-lab/tailwind/svelte/alerts/notus?ref=ns-index"
              target="_blank"
            >
              <div
                class="bg-red-600 shadow-lg rounded-lg text-center p-8"
              >
                <img
                  alt="..."
                  class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                  src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/svelte.jpg"
                />
                <p class="text-lg text-white mt-4 font-semibold">
                  Svelte
                </p>
              </div>
            </a>
            <a
              href="https://www.creative-tim.com/learning-lab/tailwind/react/alerts/notus?ref=ns-index"
              target="_blank"
            >
              <div class="bg-blue-500 shadow-lg rounded-lg text-center p-8 mt-8">
                <img
                  alt="..."
                  class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                  src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/react.jpg"
                />
                <p class="text-lg text-white mt-4 font-semibold">
                  ReactJS
                </p>
              </div>
            </a>
            <a
              href="https://www.creative-tim.com/learning-lab/tailwind/nextjs/alerts/notus?ref=ns-index"
              target="_blank"
            >
              <div
                class="bg-gray-800 shadow-lg rounded-lg text-center p-8 mt-8"
              >
                <img
                  alt="..."
                  class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                  src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/nextjs.jpg"
                />
                <p class="text-lg text-white mt-4 font-semibold">
                  NextJS
                </p>
              </div>
            </a>
          </div>
          <div class="my-4 w-full lg:w-6/12 px-4 lg:mt-16">
            <a
              href="https://www.creative-tim.com/learning-lab/tailwind/js/alerts/notus?ref=ns-index"
              target="_blank"
            >
              <div class="bg-yellow-500 shadow-lg rounded-lg text-center p-8">
                <img
                  alt="..."
                  class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                  src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/js.png"
                />
                <p class="text-lg text-white mt-4 font-semibold">
                  JavaScript
                </p>
              </div>
            </a>
            <a
              href="https://www.creative-tim.com/learning-lab/tailwind/angular/alerts/notus?ref=ns-index"
              target="_blank"
            >
              <div class="bg-red-700 shadow-lg rounded-lg text-center p-8 mt-8">
                <img
                  alt="..."
                  class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                  src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/angular.jpg"
                />
                <p class="text-lg text-white mt-4 font-semibold">
                  Angular
                </p>
              </div>
            </a>
            <a
              href="https://www.creative-tim.com/learning-lab/tailwind/vue/alerts/notus?ref=ns-index"
              target="_blank"
            >
              <div
                class="bg-green-500 shadow-lg rounded-lg text-center p-8 mt-8"
              >
                <img
                  alt="..."
                  class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
                  src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/vue.jpg"
                />
                <p class="text-lg text-white mt-4 font-semibold">
                  Vue.js
                </p>
              </div>
            </a>
          </div>
        </div>
      </div>

      <div class="w-full md:w-4/12 px-12 md:px-4 ml-auto mr-auto mt-48">
        
    
  </div>


       
      
    </div>
  </div>

  <div class="justify-center text-center flex flex-wrap mt-24">
    <div class="w-full md:w-6/12 px-12 md:px-4">
      <h2 class="font-semibold text-4xl">Beautiful Example Pages</h2>
      <p class="text-lg leading-relaxed mt-4 mb-4 text-gray-600">
        Notus Svelte is a completly new product built using our past
        experience in web templates. Take the examples we made for you and start
        playing with them.
      </p>
    </div>
  </div>
</section>
<Footer />

<template>
  <div class="w-full box-border">
    <div class="w-full bg-flblue-light">
      <div
        class="container mx-auto flex flex-row items-center py-4 lg:py-3 lg:w-5/6 lg:justify-between relative"
      >
        <img
          class="flex-initial lg:hidden absolute ml-4"
          src="../../assets/images/menu.svg"
          alt="menu"
        />
        <a href="#" class="flex-initial mx-auto lg:m-0 w-32">
          <img src="../../assets/images/logo.png" alt="logo" />
        </a>
        <div class="flex-initial hidden lg:block">
          <img
            class="inline-block w-1/4 mr-2"
            src="../../assets/images/flag-us.png"
            alt="flag-us"
          />
          <button class="inline-block">
            <span
              class="text-white text-base font-bold tracking-tight uppercase"
              >Language</span
            >
          </button>
        </div>
      </div>
    </div>
    <div class="w-full bg-flblue-dark">
      <div class="container mx-auto text-center lg:w-5/6">
        <div
          class="flex-initial w-64 sm:w-64 md:w-1/3 lg:w-1/3 xl:w-1/4 mx-auto relative"
        >
          <img
            class="absolute tred-ribbon"
            src="../../assets/images/top-red.png"
            alt="top-red"
          />
          <h1
            class="text-white text-xs font-bold tracking-tight uppercase py-3"
          >
            ranking dating sites
          </h1>
          <img
            class="flex-initial hidden lg:block lg:absolute w-4/12 lg:top-0 lg:right-0 lg:-mt-10 lg:-mr-6"
            src="../../assets/images/free-red.png"
            alt="free-red"
          />
        </div>
      </div>
    </div>
    <div class="w-full mt-8 px-4 bg-white">
      <div
        class="container border border-solid rounded border-flgray-normal box-border"
      >
        <div class="site-logo bg-flblue-light py-4">
          <img
            class="w-2/3 mx-auto"
            src="../../assets/images/friends-with-benefits.png"
            alt="friends-with-benefits"
          />
        </div>
        <div class="site-img border border-solid border-flgray-normal">
          <img
            class="w-full"
            src="../../assets/images/friend-with-benefits-single.jpg"
            alt="friend-with-benefits-single"
          />
        </div>
        <div class="table-header grid grid-cols-2 bg-flblue-light text-center">
          <div class="py-5">
            <h3 class="text-white uppercase text-base font-bold tracking-tight">
              rating
            </h3>
          </div>
          <div class="py-5">
            <h3 class="text-white uppercase text-base font-bold tracking-tight">
              popularity
            </h3>
          </div>
        </div>
        <div class="table-contents">
          <ul>
            <li class="grid grid-cols-2">
              <div class="flex-initial flex items-center justify-around">
                <span
                  class="block text-3xl font-bold tracking-tight text-flgray-dark"
                  >8.9</span
                >
                <img
                  class="flex-initial"
                  src="../../assets/images/top-heart-icon.png"
                  alt="top-heart-icon"
                />
              </div>
              <div
                class="flex flex-col justify-center px-2 py-3 border border-t-0 border-r-0 border-b-0 border-solid border-flgray-normal bg-white lg:px-12 lg:py-6"
              >
                <div
                  class="flex items-center justify-center border border-solid border-flblue-light rounded text-center px-5 py-1 lg:p-2"
                >
                  <a class="inline-block lg:hidden" href="#">
                    <img
                      class="w-5"
                      src="../../assets/images/topup.png"
                      alt="topup"
                    />
                  </a>
                  <div class="inline-block mx-1">
                    <span
                      class="text-flblue-mdark font-bold text-sm tracking-tight lg:text-lg"
                      >+1714</span
                    >
                  </div>
                  <a class="inline-block lg:hidden" href="#">
                    <img
                      class="w-5"
                      src="../../assets/images/topdown.png"
                      alt="topdown"
                    />
                  </a>
                </div>
                <div class="text-center hidden px-8 py-3 lg:p-2">
                  <a class="lg:inline-block hidden mr-3" href="#">
                    <img
                      class="w-7"
                      src="../../assets/images/topup.png"
                      alt="topup"
                    />
                  </a>
                  <a class="lg:inline-block hidden ml-3" href="#">
                    <img
                      class="w-7"
                      src="../../assets/images/topdown.png"
                      alt="topdown"
                    />
                  </a>
                </div>
                <a
                  class="block rounded bg-florange-normal text-white text-center py-1 mt-3"
                  href="#"
                  >Visit web</a
                >
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Singular",
};
</script>

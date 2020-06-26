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
    <div class="container w-full px-6">

    </div>
  </div>
</template>

<script>
export default {
  name: "Singular",
};
</script>

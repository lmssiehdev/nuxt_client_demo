<script lang="ts">
import "./main.css";
</script>

<template>
  <div class="bg-[#fff1ec] min-h-screen font-dmsans">
    <div class="px-4 max-w-screen-lg mx-auto">
      <header>
        <Navbar />
      </header>
      <div class="md:flex md:mt-32 mt-20 text-ellipsis">
        <div class="flex-1 py-10">
          <h2 class="text-6xl md:text-4xl font-bold font-moranga">
            Benefits for the best <br />
            dog owners
            <div></div>
          </h2>
          <ul class="my-5 text-lg">
            <li class="list-item list-outside">
              20-30% discounts on food, toys, and supplies.
            </li>
            <li>Vet bill protection</li>
            <li>Lorem Ipsum</li>
          </ul>
          <div class="my-5">
            <div class="text-[#61605f] max-w-sm">
              want to be a part of the club? Be notified when Nally is available
              to you
            </div>
            <form class="flex my-3 gap-4">
              <input
                type="email"
                class="px-3 py-1 min-w-[50%] rounded-md shadow"
              />
              <Button> Notify </Button>
            </form>
          </div>
        </div>
        <div class="flex-1">
          <NuxtImg src="./couple.png" />
        </div>
      </div>
    </div>
  </div>
</template>

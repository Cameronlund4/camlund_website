<template>
  <div class="" style="text-align: center; font-family: 'Open Sans'">
    <div class="flex flex-row w-full header-texture">
      <div class="flex flex-col justify-center flex-1 w-full h-auto" style="color: #3E3C3C; font-family: Oswald">
        <div>
          <div class="inline-block">
            <h1 class="text-4xl md:text-8xl">
              Cameron Lund
            </h1>
            <div class="flex flex-row justify-between">
              <p class="text-xl md:text-4xl ease-in transition-all">
                Infrastructure
              </p>
              <p class="text-xl md:text-4xl ease-in transition-all">
                -
              </p>
              <p class="text-xl md:text-4xl ease-in transition-all">
                Backend
              </p>
              <p class="text-xl md:text-4xl ease-in transition-all">
                -
              </p>
              <p class="text-xl md:text-4xl ease-in transition-all">
                Full Stack
              </p>
            </div>
          </div>
        </div>
      </div>
      <img src="~/assets/cam_cactus.png" class="w-1/3 h-auto" style="clip-path: polygon(20% 0, 0 100%, 100% 100%, 100% 0);">
    </div>

    <div class="mx-auto p-10 md:p-20">
      <h2>
        This is heavily WIP. What I want to add:
      </h2>
      <ul>
        <li>- Resume info, but cooler w/ pics</li>
        <li>- How this site is made</li>
        <li>- In depth info on Disco Studios (my company)</li>
        <li>- How I started (Minecraft)</li>
        <li>- Robotics</li>
        <li>- Personal info (cycling, etc)</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
  .header-texture {
    background:
    radial-gradient(#8191b354 3px, transparent 4px),
    radial-gradient(#8191b354 3px, transparent 4px),
    linear-gradient(#A2BDDD 4px, transparent 0),
    linear-gradient(45deg, transparent 74px, transparent 75px, #8191b354 75px, #8191b354 76px, transparent 77px, transparent 109px),
    linear-gradient(-45deg, transparent 75px, transparent 76px, #8191b354 76px, #8191b354 77px, transparent 78px, transparent 109px),
    #A2BDDD;
    background-size: 109px 109px, 109px 109px,100% 6px, 109px 109px, 109px 109px;
    background-position: 54px 55px, 0px 0px, 0px 0px, 0px 0px, 0px 0px;
  }
</style>

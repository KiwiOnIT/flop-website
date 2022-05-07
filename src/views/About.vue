<template>
<header>
    <Title>Flop website | About</Title>
</header>
<div class="h-100 d-flex flex-column">
  <div class="container-fluid d-flex justify-content-center align-items-center h-100 backgroundKiwi">
    <div>
      <p class="text-4xl">Why <span style="color: rgb(0, 148, 255);">Flop</span></p>
      <div class="w-[50%] bg-buttonmain h-1 rounded-md m-auto"></div>
      <div class="mt-24 justify-center items-center gap-8 flex flex-wrap">
        <div class="w-[350px] h-60 p-2 bg-backgroundmain rounded-xl text-center border-b-4 border-b-buttonmain shadow-black shadow-md">
            <p class="text-white text-2xl font-medium mt-[44px]">Undetected</p>
            <p class="text-zinc-300 text-xl font-light mt-3">We have the best randomization for keep you undetectable on all server.</p>
        </div>
        <div class="w-[350px] h-60 p-2 bg-backgroundmain rounded-xl text-center border-b-4 border-b-buttonmain shadow-black shadow-md">
            <p class="text-white text-2xl font-medium mt-[44px]">Bypass</p>
            <p class="text-zinc-300 text-xl font-light mt-3">You can use our clicker on all Minecraft Client. We can bypass Cheat Breaker, Lunar Client, etc...</p>
        </div>
            
        <div class="w-[350px] h-60 p-2 bg-backgroundmain rounded-xl text-center border-b-4 border-b-buttonmain shadow-black shadow-md">
            <p class="text-white text-2xl font-medium mt-[44px]">Free</p>
            <p class="text-zinc-300 text-xl font-light mt-3">Our clicker is free and everyone can use it ! </p>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>

export default {
  name: 'AboutView',
}
</script>

<style scoped>

.text-zinc-300 {
    --tw-text-opacity: 1;
    color: rgb(212 212 216/var(--tw-text-opacity));
}

.text-xl {
    font-size: 1.25rem;
}

.font-light {
    font-weight: 300;
}

.mt-3 {
    margin-top: .75rem;
}

.text-white {
    --tw-text-opacity: 1;
    color: rgb(255 255 255/var(--tw-text-opacity));
}
.font-medium {
    font-weight: 500;
}
.text-2xl {
    font-size: 1.5rem;
    line-height: 2rem;
}
.mt-\[44px\] {
    margin-top: 44px;
}


.shadow-md {
    --tw-ring-offset-shadow: 0 0 #0000;
    --tw-ring-shadow: 0 0 #0000;
    --tw-shadow-colored: 0 4px 6px -1px var(--tw-shadow-color),0 2px 4px -2px var(--tw-shadow-color);
    box-shadow: var(--tw-ring-offset-shadow,0 0 #0000),var(--tw-ring-shadow,0 0 #0000),var(--tw-shadow);
}
.shadow-black {
    --tw-shadow-color: #000;
    --tw-shadow: var(--tw-shadow-colored);
}
.bg-backgroundmain {
    background-color: rgba(33, 37, 41, 1);
}
.border-b-buttonmain {
    border-bottom: 1px solid rgb(0, 148, 255)
}
.text-center {
    text-align: center;
}
.p-2 {
    padding: .5rem;
}
.border-b-4 {
    border-bottom-width: 4px;
}
.rounded-xl {
    border-radius: .75rem;
}
.w-\[350px\] {
    width: 350px;
}
.h-60 {
    height: 15rem;
}
.flex {
    display: flex;
}
.mt-24 {
    margin-top: 6rem;
}
.gap-8 {
  gap: 2rem;
}
.bg-buttonmain {
    background-color: rgba(0, 148, 255, 1);
}
.rounded-md {
    border-radius: .375rem;
}
.w-\[50\%\] {
    width: 50%;
}
.h-1 {
    height: .25rem;
}
.text-4xl {
    font-size: 2.55rem;
    line-height: 2.5rem;
}
</style>
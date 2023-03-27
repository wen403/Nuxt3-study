<script setup lang='ts'>
definePageMeta({
  layout: 'auto',
})
</script>

<template>
  <nav bg-dark h-15 color-light p="lg:x-20 lt-lg:x-10">
    <div flex items-center justify-between h="full">
      <router-link to="/demo" text-xl font-bold>
        这是一个Demo
      </router-link>
      <ul color-light font-semibold gap-4 flex lt-lg:hidden>
        <li opacity-20 hover:opacity-50>
          第一菜单
        </li>
        <li opacity-20 hover:opacity-50>
          第二菜单
        </li>
        <li opacity-20 hover:opacity-50>
          第三菜单
        </li>
      </ul>
      <button lg:hidden btn>
        菜单
      </button>
    </div>
  </nav>

  <section bg-dark color-light p="y-10 lg:x-20 lt-lg:x-10">
    <div flex items-center gap-5 lt-md:text-center lg="justify-around">
      <div lg="w-55%">
        <h1 text-3xl font-semibold>
          一个小小的<span color-amber>Demo</span>
        </h1>
        <p m-y-5>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla repellendus aliquam saepe aut voluptas soluta
          porro beatae unde, ipsam quasi non, repellat odio rem consequatur vel quo quibusdam, dicta magni.
        </p>
        <button btn>
          Demo
        </button>
      </div>
      <img src="~/public/pwa-512x512.png" alt="vite" w="20%" lt-md:hidden>
    </div>
  </section>

  <section bg-pink color-light p="y-10 lg:x-20 lt-lg:x-10" lg="flex items-center">
    <div text-xl font-bold lg-w="50%">
      现在输入一个Demo试试
    </div>
    <div flex="~" lg-w="50%">
      <input type="text" outline-none w-full color-dark p-2 border="rd-1 rounded-r-none" placeholder="输入你的Demo">
      <button btn rounded-l-none>
        Demo
      </button>
    </div>
  </section>

  <section bg-light color-light p="y-10 lg:x-20 lt-lg:x-10">
    <div flex gap-5 justify-center lt-md="flex-col">
      <div bg-dark basis-full rd-1 p-5 flex="~ col" text-center>
        <div text-xl font-bold>
          大杯
        </div>
        <div m-y-3>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perspiciatis consectetur
        </div>
        <div>
          <button btn>
            按 钮
          </button>
        </div>
      </div>
      <div bg="#616873" basis-full rd-1 p-5 flex="~ col" text-center>
        <div text-xl font-bold>
          超大杯
        </div>
        <div m-y-3>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perspiciatis consectetur
        </div>
        <div>
          <button btn>
            按 钮
          </button>
        </div>
      </div>
      <div bg-dark basis-full rd-1 p-5 flex="~ col" text-center>
        <div text-xl font-bold>
          中杯
        </div>
        <div m-y-3>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perspiciatis consectetur
        </div>
        <div>
          <button btn>
            按 钮
          </button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang='scss'></style>

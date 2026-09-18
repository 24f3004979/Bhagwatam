<script setup lang="ts">
import pitajiPhoto from '../assets/pitaji.png'
</script>

<template>
  <section class="min-h-[calc(100vh-73px)] bg-black text-white">
    <div
      class="mx-auto flex max-w-7xl flex-col items-center gap-12 px-6 py-20
             md:flex-row md:justify-between md:py-28"
    >

      <!-- Text -->
      <div class="max-w-2xl">
        <p class="mb-5 font-mono text-sm tracking-widest text-zinc-400">
          SANSKRIT · ADHYAYANA · SEVA
        </p>

        <h1 class="font-mono text-4xl font-bold leading-tight md:text-6xl">
          [DEVRAJ ACHARYA]
        </h1>

        <p class="mt-6 max-w-xl text-lg leading-8 text-zinc-400">
          Sanskrit scholar, Bhagwat, Ramayan mul phathak, Kathakaar
          study and preservation of Bharatiya knowledge traditions.
        </p>

        <div class="mt-8 flex gap-4">
          <a
            href="#about"
            class="rounded-lg bg-white px-5 py-3 font-mono text-sm
                   font-medium text-black transition hover:bg-zinc-200"
          >
            About
          </a>

          <a
            href="#work"
            class="rounded-lg border border-zinc-700 px-5 py-3
                   font-mono text-sm text-white transition hover:bg-zinc-900"
          >
            His Work
          </a>
        </div>
      </div>

      <!-- Photograph -->
      <div class="relative">
        <div
          class="absolute -inset-3 rounded-2xl border border-zinc-800"
        ></div>

        <img
          :src="pitajiPhoto"
          alt="Portrait of [Pitaji's Name]"
          class="relative h-[420px] w-[320px] rounded-xl object-cover
                 grayscale-[20%]"
        />
      </div>

    </div>
  </section>
</template>

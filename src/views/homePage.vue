<template>
  <main>
    <!-- <div
      class="min-h-screen bg-gradient-to-b from-[#4195D5] via-[#3279AE] via-[#26628E] to-[#133F5D] w-full"
    >
      <nav>
        <div class="px-[147px] pt-[30.52px] flex flex-row justify-between">
          <img :src="logo" alt="" />
          <ul class="flex flex-row gap-8 items-center text-lg font-bold text-white">
            <li>PRODUK</li>
            <li>SOLUSI BISNIS</li>
            <li>CARA KERJA</li>
            <li>HARGA</li>
            <li>PERUSAHAAN</li>
          </ul>
          <div class="flex flex-row gap-[13px]">
            <q-btn
              rounded
              outline
              style="color: #93C854; width: 93px; height: 41px"
              label="Login"
            />
            <q-btn
              rounded
              style="background: #93C854;color: white; width: 93px; height: 41px"
              size="md"
              label="Daftar"
            />
          </div>
        </div>
      </nav>
      <div class="px-[147px] pt-[69px]"></div>
    </div> -->
    <HeroSection />
    <div></div>
    <div></div>
    <div></div>
    <div></div>
  </main>
</template>

<script lang="ts" setup>
import HeroSection from '@/components/heroSection.vue'
</script>

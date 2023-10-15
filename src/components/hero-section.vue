<template>
    <div
      class="min-h-screen bg-gradient-to-b from-[#4195D5] via-[#3279AE] via-[#26628E] to-[#133F5D] w-full text-white"
    >
      <nav>
        <div class="px-[147px] pt-[30.52px] flex flex-row justify-between">
          <img :src="logo" alt="" />
          <ul class="flex flex-row gap-8 items-center text-lg font-bold">
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
      <div class="px-[147px] pt-[69px]">
        <div class="flex flex-col pt-[73.5px]">
            <p class="font-normal text-[31px]">Simulasikan Pembayaran Lebih Cepat Dengan</p>
            <p class="font-bold text-[56px]">API Embeded <br> Finance Paper!</p>
        </div>
        <div></div>
      </div>
    </div>
</template>

<script lang="ts" setup>
import logo from '@/assets/svg/logo.svg'
</script>
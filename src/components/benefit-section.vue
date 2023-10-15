<template>
  <div class="flex flex-col items-center pt-[96px] pb-[164px] px-[148px] text-[#133F5D]">
    <div class="mb-12 font-bold text-5xl flex flex-row justify-center leading-[82px] py-[10px]">
      Manfaat yang Bisa Anda Rasakan
    </div>
    <div class="flex flex-row justify-between w-[1246px]">
      <div class="pt-[82px] flex flex-col gap-12 relative">
        <div class="flex flex-row gap-4">
          <img class="self-start w-12 h-12" :src="check" alt="" />
          <div class="flex flex-col gap-[14px]">
            <p class="font-bold text-[26px]">One Time Integration</p>
            <p class="text-[20px] font-normal w-[588px]">
              Menyediakan solusi pembiayaan dengan cara yang nyaman dan efisien bagi bisnis melalui
              satu proses integrasi.
            </p>
          </div>
        </div>
        <div class="flex flex-row gap-4">
          <img class="self-start w-12 h-12" :src="check" alt="" />
          <div class="flex flex-col gap-[14px]">
            <p class="font-bold text-[26px]">Seamless User Experience</p>
            <p class="text-[20px] font-normal w-[588px]">
                Proses pengajuan pinjaman dengan lebih mudah tanpa harus berinteraksi atau menelepon pihak pemberi pinjaman.
            </p>
          </div>
        </div>
        <div class="flex flex-row gap-4">
          <img class="self-start w-12 h-12" :src="check" alt="" />
          <div class="flex flex-col gap-[14px]">
            <p class="font-bold text-[26px]">One Submission for Multiple Financial Institutions</p>
            <p class="text-[20px] font-normal w-[588px]">
                Cukup dengan satu kali pendaftaran, Anda dapat langsung diproses secara otomatis ke beberapa lembaga keuangan.
            </p>
          </div>
        </div>
        <img class="absolute top-[110px] left-[23px] z-[-1]" :src="line" alt="">
      </div>
      <img :src="benefitPhoto" alt="" />
    </div>
  </div>
</template>

<script lang="ts" setup>
import check from '@/assets/svg/check.svg'
import line from '@/assets/svg/line.svg'
import benefitPhoto from '@/assets/images/benefit-image.png'
</script>

<template>
  <div
    class="min-h-screen bg-gradient-to-r from-[#257AB4] via-[#113955] to-[#113955] w-full text-white pt-[68px] flex flex-col items-center"
  >
    <div class="flex flex-row items-center gap-[88px] py-8 mb-[75px]">
      <img :src="footerImage" alt="" />
      <div class="flex flex-col gap-[37px] w-[797.55px]">
        <p class="font-bold text-[37px] leading-[59px]">
          Solusi Pembayaran untuk Kelancaran <br />Cashflow Bisnis via Paper id
        </p>
        <q-btn
          rounded
          style="background: #93c854; width: 274.46px; height: 56 px"
          label="Daftar Gratis Sekarang"
        />
      </div>
    </div>
    <div class="flex flex-col text-sm text-white font-normal">
      <div
        class="flex flex-row justify-between w-[1267px] border-solid border-y border-white py-[21px]"
      >
        <div>
          <img class="mb-[15px]" :src="logo" alt="" />
          <div class="flex flex-row gap-5">
            <div class="flex flex-col">
              <p class="font-bold mb-[10px]">Hubungi Kami</p>
              <div class="flex flex-row gap-[7px] mb-2">
                <img class="self-start mt-[4px]" :src="phoneIcon" alt="" />
                <div class="flex flex-col gap-[5px]">
                  <p>+62 821 1767 9137</p>
                  <p>+62 811 1098 746 (WA)</p>
                </div>
              </div>
              <div class="flex flex-row gap-[7px] mb-2">
                <img class="mt-[2px]" :src="emailIcon" alt="" />
                <p>support@paper.id</p>
              </div>
              <div class="flex flex-row gap-[7px] mb-2">
                <img class="self-start mt-[4px]" :src="addressIcon" alt="" />
                <p class="w-[168px]">
                  Jl. Sunter Garden Raya No.5D, RT.6/RW.12, Sunter Agung, Tj. Priok, Kota Jkt Utara,
                  DKI Jakarta 14350s
                </p>
              </div>
            </div>
            <div>
              <p class="font-bold mb-[10px]">Jam Operasional</p>
              <div class="flex flex-col gap-[5px]">
                <div class="flex flex-row">
                  <p class="w-[147px]">Senin - Jumat</p>
                  <p class="w-[112p]">: 07.00 - 22.00 WIB</p>
                </div>
                <div class="flex flex-row">
                  <p class="w-[147px]">Sabtu & Libur Nasional</p>
                  <p class="w-[112p]">: 08.00 - 17.00 WIB</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-row gap-[21px]">
          <div>
            <p class="font-bold mb-[7px]">Fitur Lainnya</p>
            <div class="flex flxe-row gap-[30px]">
              <div class="flex flex-col gap-[10px]">
                <p>Order dan Penawaran</p>
                <p>Akuntansi Gratis</p>
                <p>Digital Payment</p>
                <p>Manajemen Stok</p>
                <p>Laporan Keuangan</p>
                <p>One Click Share</p>
                <p>Template Invoice</p>
              </div>
              <div class="flex flex-col gap-[10px]">
                <p>Billing</p>
                <p>Financing</p>
                <p>PaperChain</p>
                <p>PaperTrade</p>
                <p>Enterprise Solution</p>
                <p>PayPer</p>
              </div>
            </div>
          </div>
          <div>
            <p class="font-bold mb-[7px]">Solusi</p>
            <div class="flex flex-col gap-[10px]">
              <p>Jual Beli</p>
              <p>Jasa</p>
              <p>F&B</p>
            </div>
          </div>
          <div>
            <p class="font-bold mb-[7px]">Perusahaan</p>
            <div class="flex flex-col gap-[10px]">
              <p>Tentang Kami</p>
              <p>Cara Kerja</p>
              <p>Karir</p>
              <p>Pricing</p>
              <p>Blog</p>
              <p>Help Center</p>
              <p>FAQ</p>
            </div>
          </div>
        </div>
      </div>
      <div class="py-[21px] flex flex-row justify-center border-solid border-b border-white">
        <div class="w-[430px] flex flex-row gap-7">
          <div class="flex flex-col gap-[5px] items-center">
            <p class="font-bold">Download Paper.id appss</p>
            <img :src="playstoreLogo" alt="" />
          </div>
          <div class="flex flex-col gap-[5px] items-center">
            <p class="font-bold">Keamanan</p>
            <div class="flex flex-row">
              <img class="mr-[13px]" :src="secureWhite" alt="" />
              <img class="mr-[5px]" :src="kanLogo" alt="" />
              <img :src="bvLogo" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="pt-[21px] pb-[111px] flex flex-row justify-between">
        <p class="font-bold text-[rgba(255,255,255,0.6)]">Copyright © 2023 Paper.id (PT Pakar Digital Global)</p>
        <div class="flex flex-row gap-[15px]">
            <img :src="youtubeIcon" alt="">
            <img :src="facebookIcon" alt="">
            <img :src="linkedinIcon" alt="">
            <img :src="instagramIcon" alt="">
        </div>
        <div class="flex flex-row gap-[35px]">
            <p>Privacy Policy</p>
            <p>Terms & Condition</p>
            <p>Sitemap</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import youtubeIcon from '@/assets/svg/youtube-icon.svg'
import instagramIcon from '@/assets/svg/instagram-icon.svg'
import facebookIcon from '@/assets/svg/facebook-icon.svg'
import linkedinIcon from '@/assets/svg/linkedin-icon.svg'
import logo from '@/assets/svg/logo.svg'
import footerImage from '@/assets/images/footer-image.png'
import phoneIcon from '@/assets/svg/phone-icon.svg'
import emailIcon from '@/assets/svg/email-icon.svg'
import addressIcon from '@/assets/svg/address-icon.svg'
import secureWhite from '@/assets/svg/secure-white.svg'
import kanLogo from '@/assets/images/kan-logo.png'
import bvLogo from '@/assets/images/bv-certification.png'
import playstoreLogo from '@/assets/images/playstore-icon.png'
</script>

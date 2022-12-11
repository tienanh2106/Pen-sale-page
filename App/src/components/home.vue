<script setup>
import Table from "./table.vue"
</script>

<template>
  <div class="w-full flex justify-center sm:pt-20 pt-0">
    <div class="sm:w-4/5 w-full">
      <!-- tabs -->
      <div class="flex justify-between flex-wrap w-full" >
        <div class="sm:w-60 w-full h-52 flex items-center justify-center rounded-2xl rounded-b-none xl:bg-zinc-200" >
          <div class="flex justify-center items-center flex-col w-52 h-40 drop-shadow-lg  bg-white rounded-2xl ">
            <div class="bg-slate-200  rounded-full h-20 w-20 flex justify-center items-center ">
              <img class="w-15 h-15 " src="../img/pencils-icon.png" alt="">
            </div>
            <span>Pencils</span>
          </div>
        </div>
        <Table class="block sm:hidden " />
        <div class="sm:w-60 w-full h-52 flex items-center justify-center rounded-2xl rounded-b-none bg-white" >
          <div class="flex justify-center items-center flex-col w-52 h-40 drop-shadow-lg  bg-white rounded-2xl ">
            <div class="bg-slate-200  rounded-full h-20 w-20 flex justify-center items-center ">
              <img class="w-15 h-15 " src="../img/market-icon.png" alt="">
            </div>
            <span>Markets</span>
          </div>
        </div>
        <div class="sm:w-60 w-full h-52 flex items-center justify-center rounded-2xl rounded-b-none bg-white" >
          <div class="flex justify-center items-center flex-col w-52 h-40 drop-shadow-lg  bg-white rounded-2xl ">
            <div class="bg-slate-200  rounded-full h-20 w-20 flex justify-center items-center ">
              <img class="w-15 h-15 " src="../img/drawing-icon.png" alt="">
            </div>
            <span>Drawing Colors</span>
          </div>
        </div>
        <div class="sm:w-60 w-full h-52 flex items-center justify-center rounded-2xl rounded-b-none bg-white" >
          <div class="flex justify-center items-center flex-col w-52 h-40 drop-shadow-lg  bg-white rounded-2xl ">
            <div class="bg-slate-200  rounded-full h-20 w-20 flex justify-center items-center ">
              <img class="w-15 h-15 " src="../img/notebooks-icon.png" alt="">
            </div>
            <span>Notebooks</span>
          </div>
        </div>
      </div>

      <!-- table -->
      <Table class="hidden xl:block" />
      <!-- table end-->

      <div class="w-full flex justify-center items-center mt-5 ">
        <div class="w-6 h-6 rounded-full bg-black mr-4"></div>
        <div class="w-6 h-6 rounded-full bg-zinc-200"></div>
      </div>

      <!-- bottom -->
      <div class="w-full pt-20">
        <div class="text-center font-bold text-5xl pb-20">Packer pen Gallery</div>
        <div class="flex">
          <div class="w-1/4">
            <img class="w-full pb-5 pt-10 h-2/5" src="../img/Rectangle3.png" alt="">
            <img class="w-full pb-10 pt 5 h-3/5" src="../img/Rectangle5.png" alt="">
          </div>
          <div class="w-2/4">
            <img class="w-full p-5 pt-0 h-2/4" src="../img/Rectangle2.png" alt="">
            <img class="w-full p-5 pt-0 pb-0 h-2/4" src="../img/Rectangle4.png" alt="">
          </div>
          <div class="w-1/4">
            <img class="w-full pt-10 pb-5 h-1/4" src="../img/Rectangle1.png" alt="">
            <img class="w-full pb-5 pt-5 h-2/4" src="../img/Rectangle6.png" alt="">
            <img class="w-full pb-10 h-1/4" src="../img/Rectangle7.png" alt="">
          </div>
        </div>
      </div>

      <div class="w-full flex justify-center items-center mt-5 pb-20">
        <div class="w-6 h-6 rounded-full bg-black mr-4"></div>
        <div class="w-6 h-6 rounded-full bg-zinc-200"></div>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>

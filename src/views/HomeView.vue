<script setup>
</script>


<template>
 <container class="bg-emerald-300 w-screen h-screen flex flex-col">
  <nav class="bg-cyan-200 w-full h-[30px]">todolist</nav>
  <content-all class="bg-rose-400 w-full h-full flex justify-center items-center">
    <content class="bg-white w-[70%] h-[650px] rounded-md flex flex-col">
      <up class="w-full flex flex-col mb-2">
        <up-1 class="w-full flex justify-center items-center gap-11">
          <input type="text" id="" class="w-[88%] h-[30px]  ml-3 px-3 py-2 bg-white border shadow-sm">
          <button class="bg-blue-500 hover:bg-rose-400 text-white font-bold py-2 px-4 rounded m-3  flex items-center justify-center">
          <span class="material-symbols-outlined">note_add</span>
        </button>
        </up-1>
        <up-2 class="w-full flex gap-2 pl-3 border-b-2 border-gray-600">
          <button class="bg-blue-500 text-white rounded-t-md p-2 focus:bg-rose-400 focus:text-black" type="button">全部</button>
          <button class="bg-blue-500 text-white rounded-t-md p-2 focus:bg-rose-400 focus:text-black" type="button">已執行</button>
          <button class="bg-blue-500 text-white rounded-t-md p-2 focus:bg-rose-400 focus:text-black" type="button">未執行</button>
        </up-2>
      </up>
      <list class="w-full grid grid-cols-3 gap-4 px-3 pt-1 text-lg">
        <list-1>執行</list-1>
        <list-2>事項</list-2>
        <list-3 class="text-center">功能</list-3>
      </list>
      <ud class="w-full px-3 overflow-y-auto">
        <ud-in class="w-full grid grid-cols-3 gap-4 items-center py-3 border-b-2 border-slate-300">
          <ud-list>
            <input class="ml-2" type="checkbox">
          </ud-list>
          <span>第一筆</span>
          <ud-list class="flex justify-center gap-2">
            <button class="bg-blue-500 text-white hover:bg-cyan-500 w-[80px] rounded p-2 flex items-center justify-center" type="button">
              <span class="material-symbols-outlined">edit_document</span>
            </button>
            <button class="bg-blue-500 text-white hover:bg-cyan-500 w-[80px] rounded p-2 flex items-center justify-center" type="button">
              <span class="material-symbols-outlined">scan_delete</span>
            </button>
          </ud-list>
        </ud-in>


        <ud-in class="w-full grid grid-cols-3 gap-4 items-center py-3 border-b-2 border-slate-300">
          <ud-list>
            <input class="ml-2" type="checkbox">
          </ud-list>
          <span>第二筆</span>
          <ud-list class="flex justify-center gap-2">
            <button class="bg-blue-500 text-white hover:bg-cyan-500 w-[80px] rounded p-2 flex items-center justify-center" type="button">
              <span class="material-symbols-outlined">edit_document</span>
            </button>
            <button class="bg-blue-500 text-white hover:bg-cyan-500 w-[80px] rounded p-2 flex items-center justify-center" type="button">
              <span class="material-symbols-outlined">scan_delete</span>
            </button>
          </ud-list>
        </ud-in>



      </ud>
      

    </content>
  </content-all>
 </container>
</template>



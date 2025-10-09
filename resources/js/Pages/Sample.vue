<script setup></script>

<template>
  <div class="my-36 flex h-[300px] border">
    <!-- 左側ブロック -->
    <div class="relative w-11 bg-red-300">
      <div
        class="absolute origin-top-left -rotate-90 bg-blue-300 flex h-11 items-center top-11"
      >
        Program
      </div>
    </div>
    <!-- 中央ブロック（可変） -->
    <div class="flex-1 bg-gray-100 p-4">
      <p>ここに自由なコンテンツが入ります</p>
    </div>

    <!-- 右側ブロック（画像） -->
    <div class="w-[200px] bg-gray-200 flex items-center justify-center">
      <img
        src="https://via.placeholder.com/150"
        alt="サンプル画像"
        class="max-w-full h-auto"
      />
    </div>
  </div>
</template>

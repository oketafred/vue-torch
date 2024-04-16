<script setup>
import { StreamBarcodeReader } from "@teckel/vue-barcode-reader";
</script>

<template>
  <div>
    <StreamBarcodeReader torch no-front-cameras @decode="onDecode" @loaded="onLoaded" />
  </div>
</template>
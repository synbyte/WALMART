<script setup>
import { ref } from 'vue';

defineProps(
  {
    item: [],
    upc: [],
    price: [],
  },
  methods(totalPrice())
);

const count = ref(5 - 12);
</script>

<template>
  <p>360-888-6199</p>
  <p>1474 NE FOURTH PLAIN</p>
  <p>VANCOUVER WA</p>
  <br />
  <p>ST# 03855 #OP 394658 #TE 3498 #TR 39585</p>
  <!-- APP MAIN BODY BEGINS HERE-->

  <div class="border-4 mx-9 border-slate-300 grid grid-cols-6 grid-rows-auto">
    <!--ITEM-->

    <div id="itemName" class="bg-red-300 my-3 col-span-2 text-left">
      <p>SAMSUN TV</p>
      <p>ITEM TWO</p>
    </div>
    <!--UPC-->
    <div id="upc" class="border-2 border-red-500 my-3 col-span-2">
      <p>0086788673423</p>
      <p>0078895748398</p>
    </div>
    <!--PRICE-->
    <div id="price" class="text-right border-2 border-red-500 my-3 col-span-2">
      <p>$1.99 X</p>
      <p>$12.74 X</p>
    </div>

    <div id="total" class="bg-yellow-300 col-span-3 col-start-4 text-right">
      <p>SUBTOTAL $14.64 X</p>
      <p>TAX</p>
      <p>TOTAL</p>
    </div>
  </div>
</template>

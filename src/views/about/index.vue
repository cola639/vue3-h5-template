<template>
  <nut-cardsstacking
    :img-url="state.imgUrl"
    :title="state.title"
    :price="state.price"
    :vipPrice="state.vipPrice"
    :shopDesc="state.shopDesc"
    :delivery="state.delivery"
    :shopName="state.shopName"
  ></nut-cardsstacking>
</template>
<script setup>
import { reactive } from "vue";
const state = reactive({
  imgUrl: "//placehold.it/350x200",
  title:
    "活蟹】湖塘煙雨 阳澄湖大闸蟹公4.5两 母3.5两 4对8只 鲜活生鲜螃蟹现货水产礼盒海鲜水",
  price: "388",
  vipPrice: "378",
  shopDesc: "自营",
  delivery: "厂商配送",
  shopName: "阳澄湖大闸蟹自营店>"
});
</script>

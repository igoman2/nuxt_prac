<template>
  <div class="container">
    <h1 class="list-title">카트 페이지</h1>
    <CartList />
    <div class="extra-panel">
      <button>구매하기</button>
    </div>
  </div>
</template>

<script>
import CartList from '@/components/CartList.vue'
// mutation의  상수화
// import { FETCH_CART_ITEMS } from '@/store'
export default {
  components: { CartList },
  // async asyncData({ store }) {
  //   // 페이지에 진입하기 전에(라우터가 작동하기 전에) 서버에서 장바구니 데이터를 불러옴
  //   await store.dispatch(FETCH_CART_ITEMS)
  // },
}
</script>

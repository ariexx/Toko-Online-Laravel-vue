<template>
  <!-- Shopping Cart Section Begin -->
  <section class="shopping-cart spad text-left">
    <div class="container">
      <div class="row">
        <!-- Detail Order -->
        <detail-order />
        <div class="col-lg-4">
          <div class="row">
            <div class="col-lg-12">
              <div class="proceed-checkout">
                <ul>
                  <li class="subtotal">ID Transaction <span>#SH12000</span></li>
                  <li class="subtotal mt-3">Subtotal <span>$240.00</span></li>
                  <li class="subtotal mt-3">Pajak <span>10%</span></li>
                  <li class="subtotal mt-3">Total Biaya <span>$440.00</span></li>
                  <li class="subtotal mt-3">Bank Transfer <span>Mandiri</span></li>
                  <li class="subtotal mt-3">No. Rekening <span>2208 1996 1403</span></li>
                  <li class="subtotal mt-3">Nama Penerima <span>Shayna</span></li>
                </ul>
                <router-link to="/success" class="proceed-btn">I ALREADY PAID</router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Shopping Cart Section End -->
</template>

<script>
import DetailOrder from "./DetailOrder.vue";
export default {
  components: { DetailOrder },
};
</script>

<style></style>

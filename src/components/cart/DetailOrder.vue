<template>
  <div class="col-lg-8">
    <div class="row">
      <div class="col-lg-12">
        <div class="cart-table">
          <table>
            <thead>
              <tr>
                <th>Image</th>
                <th class="p-name text-center">Product Name</th>
                <th>Price</th>
                <th>Action</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="cart-pic first-row">
                  <img src="img/cart-page/product-1.jpg" />
                </td>
                <td class="cart-title first-row text-center">
                  <h5>Pure Pineapple</h5>
                </td>
                <td class="p-price first-row">$60.00</td>
                <td class="delete-item">
                  <a href="#"
                    ><i class="material-icons">
                      close
                    </i></a
                  >
                </td>
              </tr>
              <tr>
                <td class="cart-pic first-row">
                  <img src="img/cart-page/product-1.jpg" />
                </td>
                <td class="cart-title first-row text-center">
                  <h5>Pure Pineapple</h5>
                </td>
                <td class="p-price first-row">$60.00</td>
                <td class="delete-item">
                  <a href="#"
                    ><i class="material-icons">
                      close
                    </i></a
                  >
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
      <!-- Detail Customer -->
      <detail-customer />
    </div>
  </div>
</template>

<script>
import DetailCustomer from "@/components/cart/DetailCustomer";
export default {
  name: "DetailedOrder",
  components: {
    DetailCustomer,
  },
};
</script>

<style></style>

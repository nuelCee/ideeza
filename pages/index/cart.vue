<template>
  <div class="md:mt-0 md:ml-6 pt-20 w-full pr-3 pl-3 md:pr-6 md:pl-0">
    <div class="w-full h-full hidden absolute bg-black left-0 top-0 flex justify-center items-center" style="z-index:999">
        <div class="w-64 h-64 bg-white"></div>
    </div>
    <div class="bg-white w-full h-full pb-6 md:block rounded-sm shadow-lg">
      <div
        class="flex md:flex w-full h-10 items-center justify-center py-0 p-6 pt-10 md:py-12 flow"
      >
        <div style="transform: translateY(15%);" class="flex flex-col w-6 md:w-10 items-center">
          <div
            class="bg-black h-12 w-12 rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/overview_icon.svg" />
          </div>
          <div class="flow_text">Overview</div>
        </div>
        <div class="h-2 w-20 bg-black rect"></div>
        <div style="transform: translateY(15%);" class="flex flex-col w-10 items-center">
          <div
            class="bg-black h-12 w-12 rounded-full act cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/cart_white.svg" />
          </div>
          <div class="act_text flow_text">Cart</div>
        </div>
        <div class="h-2 w-20 bg-black rect"></div>
        <div style="transform: translateY(15%);" class="flex flex-col w-10 items-center">
          <div
            class="bg-black h-12 w-12 rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/add_service_icon.svg" />
          </div>
          <div style="width:70px" class="flow_text">Add Service</div>
        </div>
        <div class="h-2 w-20 bg-black rect"></div>
        <div style="transform: translateY(15%);" class="flex flex-col w-10 items-center">
          <div
            class="bg-black h-12 w-12 rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/delivery_icon.svg" />
          </div>
          <div class="flow_text">Delivery</div>
        </div>
        <div class="h-2 w-20 bg-black rect"></div>
        <div style="transform: translateY(15%);" class="flex flex-col w-10 items-center">
          <div
            class="bg-black h-12 w-12 rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/payment_icon.svg" />
          </div>
          <div class="flow_text">Payment</div>
        </div>
        <div class="h-2 w-20 bg-black rect"></div>
        <div style="transform: translateY(15%);" class="flex flex-col w-10 items-center">
          <div
            class="bg-black h-12 w-12 rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/confirm_icon.svg" />
          </div>
          <div class="flow_text">Confirmation</div>
        </div>
      </div>
      <div class="w-full h-10 px-10 md:mt-6 mt-20">
        <div class="float-right">
          <div class="float-left mr-2 text-sm p-1">Optimize by:</div>
          <select class="text-sm border p-1">
            <option>Factory Cost</option>
            <option>Delivery Cost</option>
            <option>All Costs</option>
            <option>Factory Time</option>
            <option>Delivery Time</option>
            <option>All Time</option>
          </select>
        </div>
      </div>
      <div class="p-5 pt-20 md:p-10">
        <div class="w-full">
          <span class="float-left text-sm md:text-base font-bold">Lamborghini Aventado and Something</span>
          <img src="../../assets/icons/settings_icon.svg" class="float-right" width="15px" />
        </div>
        <br />
        <br />
        <hr />
        <div class="p-3 overflow-x-scroll md:overflow-auto table_con">
          <table class="table-fixed w-full">
            <thead>
              <tr class="text-left">
                <th class="w-1 pr-10 py-2">
                  <div class="w-4 h-4 border-2 rounded-sm"></div>
                </th>
                <th class="w-56 md:w-1/4 md:px-4 md:py-2">Product Name</th>
                <th class="w-56 md:w-1/4 px-4 py-2">Category</th>
                <th class="w-56 md:w-1/4 px-4 py-2">Size</th>
                <th class="w-56 md:w-1/6 px-4 py-2">Quantity</th>
                <th class="w-1/8 md:w-1/8 px-4 py-2">Cost</th>
                <th class="w-56 md:w-1/6 py-2"></th>
              </tr>
            </thead>
            <tbody>
              <itemCart v-for="(num, index) in 2" src="_nuxt/assets/icons/car_pic.svg" :key="index" />
            </tbody>
          </table>
        </div>
        <div class="w-full mt-10 md:mt-0">
          <span class="float-left text-sm md:text-base font-bold">Lamborghini Aventado and Something</span>
          <img src="../../assets/icons/settings_icon.svg" class="float-right" width="15px" />
        </div>
        <br />
        <br />
        <hr />
        <div class="p-3 overflow-x-scroll md:overflow-auto table_con">
          <table class="table-fixed w-full">
            <thead>
              <tr class="text-left">
                <th class="w-1 pr-10 py-2">
                  <div class="w-4 h-4 border-2 rounded-sm"></div>
                </th>
                <th class="w-56 md:w-1/4 md:px-4 md:py-2">Product Name</th>
                <th class="w-56 md:w-1/4 px-4 py-2">Category</th>
                <th class="w-56 md:w-1/4 px-4 py-2">Size</th>
                <th class="w-56 md:w-1/6 px-4 py-2">Quantity</th>
                <th class="w-1/8 md:w-1/8 px-4 py-2">Cost</th>
                <th class="w-56 md:w-1/6 py-2"></th>
              </tr>
            </thead>
            <tbody>
              <itemCart src="_nuxt/assets/icons/car_pic.svg" :key="index" />
            </tbody>
          </table>
        </div>
        <div class="w-full font-bold mt-10">
          <span>
            Total Cost
            <span class="t-col">$45,000</span>
          </span>
        </div>
        <div class="w-full mt-10 flex items-center justify-between">
          <div class="text-sm nxt">
            Back Step
            <img src="../../assets/icons/arrow_next.svg" class="float-left w-4 mr-2 transform rotate-180" />
          </div>
          <div class="text-sm cont-s">Continue Shopping</div>
          <div class="text-sm nxt">
            Next Step
            <img src="../../assets/icons/arrow_next.svg" class="float-right w-4 ml-2" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import itemCart from '../../components/item_cart'

export default {
  components: {
    itemCart
  }
}
</script>
<style scoped>
.t-col {
  color: #ff00c7;
}
.nxt {
  padding: 10px;
  background-color: #ff00c7;
  border-radius: 5px;
  font-size: 12px;
  color: white;
  font-weight: bold;
}
.cont-s {
  padding: 10px;
  border: 2px solid #ff00c7;
  color: #ff00c7;
  border-radius: 5px;
  font-size: 12px;
  font-weight: bold;
}
.table_con::-webkit-scrollbar {
  width: 5px;
  height: 5px;
}

.table_con::-webkit-scrollbar-track {
  background-color: #eee;
  height: 2px;
  border-radius: 100px;
}

.table_con::-webkit-scrollbar-thumb {
  background-color: #ff00c7;
  border-radius: 100px;
}
@media only screen and (max-width: 600px) {
  .cirlc img {
    transform: scale(0.5) !important;
  }
  .nxt {
    padding: 6px;
    background-color: #ff00c7;
    border-radius: 5px;
    font-size: 12px;
    color: white;
    font-weight: bold;
  }
  .cont-s {
    padding: 5px;
    border: 2px solid #ff00c7;
    color: #ff00c7;
    border-radius: 5px;
    font-size: 12px;
    font-weight: bold;
  }
}
table {
  font-size: 12px;
}
.act {
  background-color: #ff00c7 !important;
}
.act_text {
  color: #ff00c7;
}
.rect {
  background-color: #333333;
}
.rounded-full {
  background-color: #333333;
}
.flow {
  font-size: 12px;
  font-weight: bold;
}
.flow_text {
  margin-top: 10px;
}
.cirlc img {
  transform: scale(0.6);
}
</style>
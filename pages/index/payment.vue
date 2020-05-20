<template>
  <div class="md:mt-0 md:ml-6 pt-20 w-full pr-3 pl-3 md:pr-6 md:pl-0">
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
            class="bg-black h-12 w-12 rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/cart_white.svg" />
          </div>
          <div class="flow_text">Cart</div>
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
            class="bg-black h-12 w-12 act rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/payment_icon.svg" />
          </div>
          <div class="act_text flow_text">Payment</div>
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
      <div class="p-5 pt-20 md:p-10">
        <div
          class="bg-grey h-screen md:px-48 py-20 w-full rounded-sm"
          style="background-color:#f6f6f6"
        >
          <div class="flex justify-between md:w-3/4">
            <span class="text-sm">Choose Payment Method:</span>
            <img src="../../assets/icons/Visa_Inc._logo.svg" class="w-10" />
            <img src="../../assets/icons/Mastercard-logo.svg" class="w-10" />
            <img src="../../assets/icons/PayPal.svg" class="w-16" />
          </div>
          <div class="text-center md:flex justify-between mt-10">
            <div>
              <label class="text-sm">First name</label>
              <br />
              <input type="text" class="h-8 w-64 border" />
            </div>
            <div>
              <label class="text-sm">Last name</label>
              <br />
              <input type="text" class="h-8 w-64 border" />
            </div>
          </div>
          <div class="text-center md:flex justify-between mt-4">
          <div>
            <div>
              <label>End Date</label>
              <br />
              <select class="h-8 border">
                <option>mm</option>
              </select>
              <select class="h-8 border">
                <option>yyyy</option>
              </select>
            </div>
          </div>
          <div>
            <label class="text-sm">CVV</label>
            <br />
            <input type="text" class="h-8 w-64 border" />
          </div>
          </div>
        </div>
        <div class="w-full mt-10 flex items-center justify-between">
          <div class="text-sm nxt">
            Back Step
            <img
              src="../../assets/icons/arrow_next.svg"
              class="float-left w-4 mr-2 transform rotate-180"
            />
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
<style scoped>
.moda {
  backdrop-filter: blur(3px);
  background-color: #0008;
}
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
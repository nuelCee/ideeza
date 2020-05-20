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
            class="bg-black h-12 w-12 act rounded-full cirlc items-center flex flex-col justify-center"
          >
            <img src="../../assets/icons/delivery_icon.svg" />
          </div>
          <div class="act_text flow_text">Delivery</div>
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
      <div class="p-5 pt-20 md:p-10">
        <div
          class="bg-grey h-full md:px-40 py-20 w-full rounded-sm"
          style="background-color:#f6f6f6"
            >
          <div class="w-full">
            <div class="w-full text-center md:flex md:justify-between">
              <div class="text-sm">
                <span>Shipping Service:</span>
                <select class="p-2 rounded-sm border">
                  <option>Ali Express Standard</option>
                </select>
              </div>
              <div class="text-sm mt-2">
                Delivery Time:
                <span class="underline">2 to 5 business days</span>
              </div>
            </div>
            <br />
            <hr />
            <br />
            <div class="flex items-center mb-2">
              <div class="h-4 w-4 border-2 border-black bg-white mr-2"></div>Use the same address from my settings
            </div>
            <div class="text-center md:flex justify-between">
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
            <div class="text-center md:flex justify-between mt-10">
              <div>
                <label class="text-sm">Phone number</label>
                <br />
                <input type="text" class="h-8 w-64 border" />
              </div>
              <div>
                <label class="text-sm">E-mail</label>
                <br />
                <input type="text" class="h-8 w-64 border" />
              </div>
            </div>
            <div class="text-center md:flex justify-between mt-10">
              <div>
                <label class="text-sm">Country</label>
                <br />
                <select class="w-64 h-8 border"></select>
              </div>
              <div>
                <label class="text-sm">City</label>
                <br />
                <select class="w-64 h-8 border"></select>
              </div>
            </div>
            <div class="text-center md:flex justify-between mt-10 mb-10">
              <div>
                <label class="text-sm">Address</label>
                <br />
                <input type="text" class="h-8 w-64 border" />
              </div>
              <div>
                <label class="text-sm">Zipcode</label>
                <br />
                <input type="text" class="h-8 w-64 border" />
              </div>
            </div>
          </div>
          <hr>
        <div class="flex justify-end mt-6 mr-4 md:mr-0">
            Shipping Cost: <span class="ml-2 font-bold">$50</span>
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
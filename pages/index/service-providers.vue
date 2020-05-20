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
      <div class="w-full flex justify-between h-10 px-1 md:px-10 md:mt-6 mt-20">
        <div class="flex items-center">
          <div class="mr-2 text-sm p-1">Type:</div>
          <select class="text-sm border p-1">
            <option>Car</option>
            <option>Table</option>
            <option>Chare</option>
          </select>
        </div>
        <div class="flex items-center">
          <div class="mr-2 text-sm p-1">Optimize by:</div>
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
      <div class="p-5 pt-20 md:p-10 mt-6">
        <div class="w-full overflow-x-scroll md:overflow-auto table_con">
          <div class="w-auto md:w-3/4 h-auto flex justify-between">
            <div class="flex">
              <div>
                <img
                  src="../../assets/icons/sander-weeteling-dq7Wlq_evnc-unsplash.svg"
                  class="w-12"
                />
                <span class="text-sm">Fabrication</span>
              </div>
              <div class="ml-4 w-40 md:w-auto">
                <span>John Doe</span>
                <br />
                <span class="text-sm t-col">Frizty Studio LTD</span>
              </div>
            </div>
            <div>
              <select class="text-sm border p-1 mr-20 md:mr-0">
                <option>Fedex</option>
                <option>Dhl</option>
                <option>UPS</option>
                <option>Regular</option>
              </select>
              <img src="../../assets/icons/arrow_rg.svg" class="w-24" />
            </div>
            <div class="flex">
              <div>
                <img
                  src="../../assets/icons/sander-weeteling-dq7Wlq_evnc-unsplash.svg"
                  class="w-12"
                />
                <span class="text-sm">Assembly</span>
              </div>
              <div class="ml-4 w-40 md:w-auto">
                <span>John Doe</span>
                <br />
                <span class="text-sm t-col">Frizty Studio LTD</span>
              </div>
            </div>
            <div>
              <select class="text-sm border p-1">
                <option>Regular</option>
                <option>Dhl</option>
                <option>UPS</option>
                <option>Regular</option>
              </select>
              <img src="../../assets/icons/arrow_cd.svg" class="w-20 mt-2" />
            </div>
          </div>
          <div class="w-full flex mt-10 justify-between">
            <div class="flex">
              <div>
                <img
                  src="../../assets/icons/sander-weeteling-dq7Wlq_evnc-unsplash.svg"
                  class="w-12"
                />
                <span class="text-sm">Dealer</span>
              </div>
              <div class="ml-4 w-32 md:w-auto">
                <span>John Doe</span>
                <br />
                <span class="text-sm t-col">Frizty Studio LTD</span>
              </div>
            </div>
            <div class="ml-10 md:ml-16 mr-20 md:mr-0">
              <select class="text-sm border p-1">
                <option>UPS</option>
                <option>Dhl</option>
                <option>UPS</option>
                <option>Regular</option>
              </select>
              <img src="../../assets/icons/arrow_cu.svg" class="w-24 -mt-16 ml-2" />
            </div>
            <div class="flex ml-64 md:ml-64">
              <div>
                <img
                  src="../../assets/icons/sander-weeteling-dq7Wlq_evnc-unsplash.svg"
                  class="w-12"
                />
                <span class="text-xs">Combining</span>
              </div>
              <div class="ml-4 w-40 md:w-auto">
                <span>John Doe</span>
                <br />
                <span class="text-sm t-col">Frizty Studio LTD</span>
              </div>
            </div>
            <div class="arrow-rg">
              <img src="../../assets/icons/arrow_rg.svg" class="w-20 mt-2" />
            </div>
            <div class="flex flex-col w-40 ml-20 md:w-auto md:ml-0">
              <img src="../../assets/icons/home-run.svg" class="mt-2 transform scale-75" />
              <p class="text-sm w-20">Your Home</p>
            </div>
          </div>
          <div class="flex mt-20 justify-end mr-56 w-full md:w-auto las-col">
            <div class="flex mr-16">
              <div>
                <img
                  src="../../assets/icons/sander-weeteling-dq7Wlq_evnc-unsplash.svg"
                  class="w-12"
                />
                <span class="text-sm">CNC Machining</span>
              </div>
              <div class="ml-4">
                <span>John Doe</span>
                <br />
                <span class="text-sm t-col">Frizty Studio LTD</span>
              </div>
            </div>
            <div>
              <select class="text-sm border p-1">
                <option>DHL</option>
                <option>Dhl</option>
                <option>UPS</option>
                <option>Regular</option>
              </select>
              <img src="../../assets/icons/arrow_cu.svg" class="w-24 -mt-16 ml-2" />
            </div>
          </div>
        </div>
        <div class="w-full mt-10 flex items-center justify-between">
          <div class="text-sm cont-s">Go Back</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
</script>
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
  .las-col {
    width: 160% !important;
  }
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
  .arrow-rg {
    display: contents;
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
<template>
    <div class="w-full h-full fixed left-0 top-0 flex justify-center items-center moda px-3" style="z-index:9999;">
        <div class="w-full md:w-2/6 h-auto bg-white rounded-lg p-6">
        <span class="font-bold">Lamborghini</span>
        <p class="text-sm float-right t-col pointer" @click="show()">Close</p>
        <div class="w-full flex items-center justify-between mt-4">
          <div>
            <span class="font-bold text-sm">Category</span>
            <div class="text-sm pt-2">Electronics</div>
            <div class="text-sm pt-2">Code</div>
          </div>
          <div>
            <span class="font-bold text-sm">{{type === "shipping" ? "Shipping" : "Manufacturer"}}</span>
            <div class="text-sm pt-2 flex items-center">
              <div class="truncate w-24">PCB way, Chaaaa</div>
              <img src="../assets/icons/edit_icon.svg" class="w-4 mr-2 ml-2">
              <img src="../assets/icons/delete_icon.svg" class="w-3 mr-2 ml-2">
            </div>
            <div class="text-sm pt-2 flex items-center">
              <div class="truncate w-24">PCB way, Chaaaa</div>
              <img src="../assets/icons/edit_icon.svg" class="w-4 mr-2 ml-2">
              <img src="../assets/icons/delete_icon.svg" class="w-3 mr-2 ml-2">
            </div>
          </div>
          <div>
            <span class="font-bold text-sm">Price</span>
            <div class="text-sm pt-2">$10,000</div>
            <div class="text-sm pt-2">$10,000</div>
          </div>
        </div>
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return{
        }
    },
    props: {
    type: String,
    show: Function,
  }
}
</script>

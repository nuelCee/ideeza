<template>
    <tr>
      <td>
        <div class="w-4 h-4 border-2 rounded-sm"></div>
      </td>
      <td class="px-4 py-2 flex items-center">
        <img :src="src" width="20%" class="float-left" />
        <div class="ml-3">Lamboghini</div>
      </td>
      <td class="px-4 py-2">Electronics, Cover</td>
      <td class="px-4 py-2">30mm x 60mm x 70mm</td>
      <td class="px-4 py-2">
        <div class="flex items-center justify-center w-12">
          <div class="mr-4 ml-4 text-lg t-col">+</div>
          <div class="w-2">1</div>
          <div class="mr-4 ml-4 text-lg t-col">-</div>
        </div>
      </td>
        <td class="px-4 py-2">$20,000</td>
      <td class="px-4 py-2">
        <img @click="showMore = !showMore" src="../assets/icons/more.svg" width="3%" class="float-right w-1 opts" />
        <div v-if="showMore" class="bg-white p-2 md:mt-6 md:ml-6 md:absolute shadow-md rounded-md opte">
          <span class="t-col">Project Details</span>
          <br />
          <br />
          <span>Delete</span>
        </div>
      </td>
    </tr>
</template>
<script>
    export default {
        data(){
            return ({
                showMore: false,
            });
        },
        props: {
            src: String,
        }
    }
</script>
<style scoped>
.t-col{
  color: #ff00c7;
}
.opts{
    cursor: pointer;
}
@media only screen and (max-width: 600px) {
    .opte{
    z-index: 1000;
    position: absolute;
    right: 0;
    margin-right: 50px;
    margin-top: 20px;
}
}
</style>
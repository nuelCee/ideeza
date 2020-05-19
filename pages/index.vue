<template>
  <div>
          <div v-show="mobile_nav" class="fixed h-screen md:hidden w-full bg-white mobile_nav" style="z-index:1000">
              <div class="px-40">
              <div @click="hide_mobileNav()" class="text-center flex items-center justify-center mt-3 p-1 px-4 text-sm rounded-full clo border-2">Close</div>
              </div>
              <div class="flex items-center justify-center flex-col mt-10">
              <ul class="sidebar_ul">
               <li><img src="../assets/icons/dashboard_iconnn.svg" class="m-0 float-left"><span class="ml-3">Dashboard</span></li>
               <li><img src="../assets/icons/rocket-outline.svg" class="m-0 float-left"><span class="ml-3">My Projects</span></li>
               <li><img src="../assets/icons/list-outline.svg" class="m-0 float-left"><span class="ml-3">News Feed</span></li>
               <li><img src="../assets/icons/document-outline.svg" class="m-0 float-left"><span class="ml-3">My Notes</span></li>
               <li><img src="../assets/icons/chatbubbles-outline.svg" class="m-0 float-left"><span class="ml-3">Messages</span></li>
               <li><img src="../assets/icons/book-outline.svg" class="m-0 float-left"><span class="ml-3">Blog</span></li>
           </ul>
           </div>
          </div>
      <nav class="bg-white fixed">
          <div class="logo_c">
              <svg id="logo" class="float-left" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs><clipPath id="clip-path" transform="translate(0 0)"><path d="M6.87,35.82c-5.68,0-3.91,6.92-1.21,8.93a2.71,2.71,0,0,0,1.62.58c3.69,0,6.34-8.83.46-9.46a8.46,8.46,0,0,0-.87,0" style="fill:none"/></clipPath><pattern id="pattern" data-name="pattern" width="14" height="11" patternTransform="matrix(0.91, 0, 0, -0.89, 1.7, 1049.48)" patternUnits="userSpaceOnUse" viewBox="0 0 14 11"><rect width="14" height="11" style="fill:none"/><image width="14" height="11" transform="matrix(1, 0, 0, -1, 0, 11)" xlink:href="ai158981955411.png" style="isolation:isolate"/></pattern><clipPath id="clip-path-2" transform="translate(0 0)"><path d="M11.71,19.87v12c3.29-1.48,5-5.17.4-11.46-.13-.18-.26-.36-.4-.53" style="fill:none"/></clipPath><pattern id="pattern-2-2" data-name="pattern-2" width="6" height="13" patternTransform="matrix(0.86, 0, 0, -0.94, 12.99, 1060.52)" patternUnits="userSpaceOnUse" viewBox="0 0 6 13"><rect width="6" height="13" style="fill:none"/><image width="6" height="13" transform="matrix(1, 0, 0, -1, 0, 13)" xlink:href="ai158981955412.png" style="isolation:isolate"/></pattern></defs><title>idee</title><g id="Group_34" data-name="Group 34"><path id="Path_90" data-name="Path 90" d="M12.11,20.4c-4.15-5.68-8.54-3.71-10.56,0S-1.28,29.25,4,31.79s16-.58,8.12-11.39" transform="translate(0 0)" style="fill:#561f80"/><path id="Path_91" data-name="Path 91" d="M7.74,35.87C1,35.14,2.83,42.64,5.66,44.75,10,48,14.46,36.59,7.74,35.87" transform="translate(0 0)" style="fill:#561f80"/><g id="Group_29" data-name="Group 29"><g style="clip-path:url(#clip-path)"><g id="Group_28" data-name="Group 28"><rect id="Rectangle_3" data-name="Rectangle 3" x="1.05" y="35.69" width="12.69" height="9.77" style="fill:url(#pattern)"/></g></g></g><path id="Path_93" data-name="Path 93" d="M24.36,49.94a1.13,1.13,0,0,1-1.13,1.15h0a1.17,1.17,0,0,1-1.15-1.15v-16a1.17,1.17,0,0,1,1.15-1.15,1.14,1.14,0,0,1,1.15,1.13V49.94Z" transform="translate(0 0)" style="fill:#2a2929"/><path id="Path_94" data-name="Path 94" d="M29.36,34.05l.1-.1a4.14,4.14,0,0,1,3-1.21h4.19a7.9,7.9,0,0,1,7.81,7.84v2.66a7.89,7.89,0,0,1-7.81,7.85h-4.2a4.13,4.13,0,0,1-2.95-1.22l-.1-.13a4,4,0,0,1-1.12-2.82v-10a4.1,4.1,0,0,1,1.12-2.82ZM31,35.66a1.79,1.79,0,0,0-.46,1.25v10A1.81,1.81,0,0,0,31,48.17l.06.06a1.81,1.81,0,0,0,1.31.56h4.2a5.41,5.41,0,0,0,3.88-1.64h0a5.55,5.55,0,0,0,1.61-3.91V40.59a5.55,5.55,0,0,0-1.61-3.91h0A5.41,5.41,0,0,0,36.61,35h-4.2a1.73,1.73,0,0,0-1.31.56Z" transform="translate(0 0)" style="fill:#2a2929"/><path id="Path_95" data-name="Path 95" d="M49.31,40.75H59.68a1.17,1.17,0,0,1,0,2.33H49.31v.16a5.58,5.58,0,0,0,5.52,5.55h5.94a1.15,1.15,0,1,1,0,2.3H54.83A7.88,7.88,0,0,1,47,43.25V40.59a7.88,7.88,0,0,1,7.85-7.85h5.94a1.15,1.15,0,0,1,0,2.3H54.83a5.58,5.58,0,0,0-5.52,5.55Z" transform="translate(0 0)" style="fill:#2a2929"/><path id="Path_96" data-name="Path 96" d="M65.35,40.75H75.72a1.17,1.17,0,0,1,0,2.33H65.35v.16a5.57,5.57,0,0,0,5.51,5.55h6a1.15,1.15,0,0,1,0,2.3h-6A7.88,7.88,0,0,1,63,43.25V40.59a7.88,7.88,0,0,1,7.84-7.85h6a1.15,1.15,0,0,1,0,2.3h-6a5.57,5.57,0,0,0-5.51,5.55Z" transform="translate(0 0)" style="fill:#2a2929"/><path id="Path_97" data-name="Path 97" d="M113.93,49.85l-1.58-14a3.26,3.26,0,0,0-3.41-3.11l-.25,0a4.71,4.71,0,0,0-2,.79,4,4,0,0,0-.63.54c-.2.21-9.54,12.5-11.23,14.72h-12a1.31,1.31,0,0,1-1.34-1.28v-.07a1.39,1.39,0,0,1,.65-1.12l12-7a3.62,3.62,0,0,0,1.73-3,3.55,3.55,0,0,0-3.53-3.58H80.54a1.12,1.12,0,1,0,0,2.23H92.32a1.35,1.35,0,0,1,1.31,1.35A1.19,1.19,0,0,1,93,37.43l-12,7a3.55,3.55,0,0,0,1.8,6.63H95a2.32,2.32,0,0,0,1.67-.92c1.77-2.33,11.13-14.66,11.26-14.77a1.62,1.62,0,0,1,.53-.29A1.89,1.89,0,0,1,109,35c.72,0,1.08.43,1.17,1.14l.93,8.16h-6.87a1.12,1.12,0,1,0,0,2.23h7.12l.4,3.55a1.12,1.12,0,1,0,2.22-.26Z" transform="translate(0 0)" style="fill:#2a2929"/><path id="Path_98" data-name="Path 98" d="M46.66,12.09C46.66,5.41,38.47,0,28.37,0,20.8,0,14.62,3.27,11.83,7.26a7.62,7.62,0,0,0,.64,9.6c2.21,2.57,3.1,4.12,5,8.66,1.36,3.27,4.29,4.27,7.55,4.29,2.68,0,5.18-1.84,6.77-3.72a20.2,20.2,0,0,1,7.53-4.91c4.64-1.53,7.35-4.76,7.35-9.09" transform="translate(0 0)" style="fill:#561f80"/><g id="Group_33" data-name="Group 33"><g style="clip-path:url(#clip-path-2)"><g id="Group_32" data-name="Group 32"><rect id="Rectangle_5" data-name="Rectangle 5" x="11.61" y="19.78" width="5.18" height="12.21" style="fill:url(#pattern-2-2)"/></g></g></g><path id="Path_101" data-name="Path 101" d="M35.56,11.75c-.23-.23-2.35-1.46-3.1-2a36,36,0,0,0-5.05-2.7c-.49-.2-.93-.53-1.41-.77-.67-.34-1.35-.67-2-1a1,1,0,0,0-1.4.28,1.06,1.06,0,0,0-.16.67c0,.54.06,12.72.05,13.59A1.7,1.7,0,0,0,24,21.74a1.75,1.75,0,0,0,.51,0,4.15,4.15,0,0,0,1.45-.61,23.33,23.33,0,0,0,2.48-1.54c1.2-.83,6.28-5.67,7-6.19A1,1,0,0,0,35.75,12a.71.71,0,0,0-.19-.23" transform="translate(0 0)" style="fill:#fff"/></g></svg>
          </div>
          <div>
              <svg @click="show_mobileNav()" id="menu" class="md:float-left mt-2 mr-5 absolute top-0 right-0 md:relative h-16 w-10 md:mt-3 ml-16"><title>menu</title><g id="menu"><g id="Ellipse_62" data-name="Ellipse 62"><circle cx="25" cy="25" r="25" style="fill:none"/><circle cx="25" cy="25" r="24.5" style="fill:none;stroke:#eee"/></g><g id="menu-outline"><line id="Line_23" data-name="Line 23" x1="15" y1="19" x2="35" y2="19" style="fill:none;stroke:#999;stroke-linecap:round;stroke-miterlimit:10;stroke-width:2px"/><line id="Line_24" data-name="Line 24" x1="15" y1="25" x2="35" y2="25" style="fill:none;stroke:#999;stroke-linecap:round;stroke-miterlimit:10;stroke-width:2px"/><line id="Line_25" data-name="Line 25" x1="15" y1="31" x2="35" y2="31" style="fill:none;stroke:#999;stroke-linecap:round;stroke-miterlimit:10;stroke-width:2px"/></g></g></svg>
          </div>
          <div class="hidden md:block">
              <svg id="nav_bg" class="float-right"><defs><linearGradient id="linear-gradient" x1="-339.19" y1="597.28" x2="-337.75" y2="596.11" gradientTransform="matrix(1239.91, 0, 0, -119.29, 419991.54, 71216.21)" gradientUnits="userSpaceOnUse"><stop offset="0" stop-color="#561f80"/><stop offset="1" stop-color="#f301c3"/></linearGradient><linearGradient id="linear-gradient-2" x1="-337.98" y1="597.01" x2="-337.98" y2="596.01" gradientTransform="matrix(646.8, 0, 0, -120, 219519.81, 71641)" xlink:href="#linear-gradient"/></defs><title>nav_dbg</title><g id="Group_1691" data-name="Group 1691"><path id="Intersection_3" data-name="Intersection 3" d="M43.59,120C-22.66,69.71,7.22.71,7.22.71H1240.41V120Z" transform="translate(-0.5)" style="fill:url(#linear-gradient)"/><path id="Intersection_4" data-name="Intersection 4" d="M1024.52,120A104.32,104.32,0,0,0,865,120H593.61A355.28,355.28,0,0,1,640.37,0h600V120Z" transform="translate(-0.5)" style="fill:url(#linear-gradient-2)"/></g></svg>
          </div>
          <ul class="fixed top-0 right-0 hidden md:block">
              <li class="w-10"><svg id="help_circle"><title>help-circle-outline</title><g id="help-circle-outline"><path id="Path_198" data-name="Path 198" d="M11.28,1A10.28,10.28,0,1,0,21.56,11.28h0A10.28,10.28,0,0,0,11.28,1Z" style="fill:none;stroke:#fff;stroke-miterlimit:10;stroke-width:2px"/><path id="Path_199" data-name="Path 199" d="M8,8.14a2.88,2.88,0,0,1,1.14-1.9,3.39,3.39,0,0,1,2.13-.68,3.57,3.57,0,0,1,1.55.26,2.68,2.68,0,0,1,1.72,2.4c0,1.52-1,2.21-2.12,3A2.76,2.76,0,0,0,11,13.62" style="fill:none;stroke:#fff;stroke-linecap:round;stroke-miterlimit:10;stroke-width:2px"/><circle id="Ellipse_51" data-name="Ellipse 51" cx="10.78" cy="16.78" r="1.5" style="fill:#fff"/></g></svg></li>
              <li class="w-10">
                  <svg id="cart_outline"><title>cart-outline</title><g id="cart-outline"><circle id="Ellipse_56" data-name="Ellipse 56" cx="7.89" cy="18.73" r="1" style="fill:none;stroke:#fc00c5;stroke-linecap:round;stroke-linejoin:round;stroke-width:2px"/><circle id="Ellipse_57" data-name="Ellipse 57" cx="18.89" cy="18.73" r="1" style="fill:none;stroke:#fc00c5;stroke-linecap:round;stroke-linejoin:round;stroke-width:2px"/><path id="Path_1217" data-name="Path 1217" d="M1,1H4.22L6.63,14.68H19.51" style="fill:none;stroke:#fc00c5;stroke-linecap:round;stroke-linejoin:round;stroke-width:2px"/><path id="Path_1218" data-name="Path 1218" d="M6.63,11.46H19.18a.39.39,0,0,0,.39-.32L21,3.9a.4.4,0,0,0-.31-.48H5" style="fill:none;stroke:#fc00c5;stroke-linecap:round;stroke-linejoin:round;stroke-width:2px"/></g></svg>
                </li>
              <li class="w-10">
                  <svg id="notification_icon"><title>notifications-outline</title><g id="notifications-outline"><path id="Path_196" data-name="Path 196" d="M20.91,18.34c-1.47-1.8-2.5-2.71-2.5-7.66,0-4.54-2.31-6.15-4.22-6.94a1,1,0,0,1-.57-.6,2.55,2.55,0,0,0-5,0,1,1,0,0,1-.57.6c-1.91.79-4.22,2.4-4.22,6.94,0,5-1,5.87-2.51,7.66a1.16,1.16,0,0,0,1,1.87H19.93a1.16,1.16,0,0,0,1-1.87Z" transform="translate(-0.04 0)" style="fill:none;stroke:#fff;stroke-linecap:round;stroke-linejoin:round;stroke-width:2px"/><path id="Path_197" data-name="Path 197" d="M14.76,20.2v.92a3.66,3.66,0,0,1-7.32,0h0V20.2" transform="translate(-0.04 0)" style="fill:none;stroke:#fff;stroke-linecap:round;stroke-linejoin:round;stroke-width:2px"/></g></svg>
            </li>
              <li><img src="../assets/img/dp.png"></li>
              <li>
                  <span class="float-left">Nick Rough</span>
                  <span class="float-left"><svg id="arrow_down"><title>arrow_down</title><path id="arrow_down" data-name="arrow down" d="M4.25,3.39,7.46.18a.6.6,0,0,1,.85,0h0a.62.62,0,0,1,0,.86L4.68,4.68a.61.61,0,0,1-.84,0L.18,1A.6.6,0,0,1,1,.18Z" transform="translate(0 0)" style="fill:#fff"/></svg></span>
              </li>
          </ul>
      </nav>
    <div class="md:flex">
        <div class="hidden md:block bg-white shadow-2xl pt-20 pl-5 w-1/4">
           <ul class="sidebar_ul fixed">
               <li><img src="../assets/icons/dashboard_iconnn.svg" class="m-0 float-left"><span class="ml-3">Dashboard</span></li>
               <li><img src="../assets/icons/rocket-outline.svg" class="m-0 float-left"><span class="ml-3">My Projects</span></li>
               <li><img src="../assets/icons/list-outline.svg" class="m-0 float-left"><span class="ml-3">News Feed</span></li>
               <li><img src="../assets/icons/document-outline.svg" class="m-0 float-left"><span class="ml-3">My Notes</span></li>
               <li><img src="../assets/icons/chatbubbles-outline.svg" class="m-0 float-left"><span class="ml-3">Messages</span></li>
               <li><img src="../assets/icons/book-outline.svg" class="m-0 float-left"><span class="ml-3">Blog</span></li>
           </ul>
        </div>
        <nuxt-child />
    </div>
  </div>
</template>
<script>
export default {
    data(){
        return{
            mobile_nav: false,
        }
    },
    mounted(){
        
    },
    methods:{
        show_mobileNav(){
            this.mobile_nav = true;
        },
        hide_mobileNav(){
            this.mobile_nav = false;
        }
    }
}
</script>

<style scoped>
#menu, .clo{
    cursor: pointer;
}
.clo{
    border-color: #FF00C7;
    color: #FF00C7;
}
@media only screen and (max-width: 600px) {
    .logo_c{
    display: flex;
    align-items: center;
    justify-content: center;
}
#logo{
    max-width: 26%!important;
    transform: scale(0.6)!important;
    height: 64px;
}
nav{
    box-shadow: 0px 2px 2px 0 rgba(0,0,0,0.40)!important;
    z-index: 999!important;
}
}
.sidebar_ul li{
    padding: 20px;
    font-weight: 600;
}
.sidebar_ul li img{
    margin-top: 2px;
    transform: scale(0.8);
}
nav{
    height: 64px;
    overflow: hidden;
    z-index: 999;
    width: 100%;
    box-shadow: 280px 2px 10px 0 rgba(0,0,0,0.40);
}
#logo{
    max-width: 10%;
    transform: scale(0.7);
    height: 64px;
}
#nav_bg{
width: 70%;
height: 100%;
margin-top: -50px;
}
nav ul{
    width: 40%;
    top: 10px;
    right: -170px;
}
nav ul li{
    color: white;
    width: 23%;
    padding: 10px;
    float: left;
}
nav ul li svg{
    width: 100%;
    height: 25px;
    transform: scale(0.7);
}
nav ul li img{
    margin-top: -5px;
    float: right;
}
.w-10{
    width: 8%!important;
}
#arrow_down{
    float: right;
    width: 10px;
    height: 10px;
    margin-top: 10px;
    transform: scale(1.1);
    margin-left: 5px;
}
#menu{
    transform: scale(0.9);
}
</style>
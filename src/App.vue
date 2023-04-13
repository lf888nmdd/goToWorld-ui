<template>
  <div style="width: 100vw;height: 100vh;" >
    <!-- <waterfall>
      <div v-for="(item,index) in dist" :key="index" >
        <img :src="item.img" alt="">
      </div>
    </waterfall> -->
    <drag>
      <div slot="dragleft" style="width: 200px;height: 200px;background-color: red;"></div>
      <div slot="dragright" style="width: 200px;height: 200px;background-color: red;"></div>
    </drag>

  </div> 
</template>

<script>
// import waterfall from './package/waterfall/index.vue'
import drag from './package/drag/index.vue'
export default{
  components:{
    // waterfall,
    drag
  },
  // data(){
  //   return {
  //     dist:[
  //       {
  //         img:'https://img1.baidu.com/it/u=2849528710,3350980061&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=650'
  //       },
  //       {
  //         img:'https://img1.baidu.com/it/u=1098037138,1075157789&fm=253&fmt=auto&app=138&f=PNG?w=744&h=500'
  //       },
  //       {
  //         img:'https://img0.baidu.com/it/u=2438846559,3448250408&fm=253&fmt=auto&app=138&f=JPEG?w=580&h=386'
  //       },
  //       {
  //         img:'https://img0.baidu.com/it/u=1107004657,3708192167&fm=253&fmt=auto&app=138&f=JPEG?w=499&h=280'
  //       },
  //       {
  //         img:'https://img2.baidu.com/it/u=1099578957,1855441338&fm=253&fmt=auto&app=138&f=JPEG?w=508&h=500'
  //       },
  //       {
  //         img:'https://img1.baidu.com/it/u=2957104364,3904576959&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=600'
  //       },
  //     ]
  //   }
  // }
}

</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
}

</style>

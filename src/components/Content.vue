<template>
    <div class="back">
        <div class="text-content">
            <h1>{{title}}</h1>
            <p>Discover the next-level digital asset</p>
            <p>trading experience on a regulated platfrom</p>
        </div>
        <img class="foot-photo" src="../assets/Path 1910.png"/>
    </div>
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {
    title:'WESERVE TOKEN (WE)',
    };
  },
};
</script>

<style>
.back{
   background-color: rgb(245, 245, 107);
   width: 100%;
   height: 1034px;
   overflow: hidden;
   display: flex;
   align-items: center;
   justify-content: center;
   position: relative;
   
}
.foot-photo{
    position: absolute;
    top: 895px;
    opacity: 1;
    display: flex;
    align-items: center;

}
</style>
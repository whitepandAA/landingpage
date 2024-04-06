<script>
    import img2 from "../assets/images/co_homepage_hero_image.webp"
    import awardimg from "../assets/images/download.webp"
    import Transitions from "./Transitions.svelte"; 
</script>

<div class="sub-header" style="padding-top:50px">
 <span class="text"><span>
    <button class="threeoption">
        <span class="hover">Email validation</span >,<span class="hover">Email Finder</span>&<span class="hover">Prospecting service</span>
       </button>
 </span>
  <span><h2 class="heading">
    <Transitions/>
 </h2></span>
   
 </span>
 <div class="allimg">
    <div class="img">
        <img alt=" img2"src={img2} style="height: 550px;">
      </div>
     <div class="awardimg"><img alt="ij" src={awardimg}></div>
     </div>
 </div>
 

<style>
    .allimg{
        display: flex;
        justify-content: space-between;
    }.img{
        margin-right: 120px;
        width:10px
    }
    .awardimg{
        align-self: center;
        position: fixed;
        right:0px;
    }
    .sub-header{
        display: flex;
        justify-content: space-between;
        
        
    }
    .img{
        width:min-content;
        height: min-content;
    }
    .threeoption{
        background-color: rgb(55, 54, 54);
        color:white;
        margin-top: 45px;
        margin-left:85px;
        border-radius: 15px;
    }
    .hover:hover{
        color: rgb(242, 114, 10);
        transition:0.3s
    }
</style>
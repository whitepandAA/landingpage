<script>
    import {fly,fade,blur} from "svelte/transition"
    import {quintIn, quintInOut, quintOut} from "svelte/easing"
    import tz from "../assets/tabimages/zapier.webp"
    import tw from "../assets/tabimages/wordpress.webp"
    import tm from "../assets/tabimages/mailchimp.webp"
    import td from "../assets/tabimages/googlesheet.webp"
    import ta from "../assets/tabimages/activecampaign.webp"
    import str1 from "../assets/tab2/download.webp"
    import str2 from "../assets/tab2/d1.webp"
    import m1 from "../assets/tab2/d2.webp"
    import m2 from "../assets/tab2/d.webp"
    let words=["DISCOVER","VERIFY","PROSPECT"]
    let count=0;
    
    setInterval(()=>{
        count+=1;
        
        if(count==3){
            count=0;
        }
        console.log(count)
    },1500) 
</script>
<div class="para">
    <h1><div>One-stop solution to<br></div> 
       
        {#each words as word ,i}
        {#if count===i }
        <span style="display:flex;justify-content:left"class=" trns" transition:blur= {{duration:1000,delay:500,amount:50}}  >
          <span style="position:absolute">{ word} </span>
        </span>
        {/if}
           
       {/each}
        
       &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp<span>ideal user</span></h1>
        
   

    <div>
     <p>Drive sustainable business growth with <u id="under">4-fold higher ROI</u> by expanding your reach, lowering hard bounces, and improving deliverability rates. Boost your sales and marketing efforts with our enriched prospecting, email finder and email validation services.</p>
    </div>
    <div ><button class="button">Get 100 Credits-Try it Now</button></div>
    <div style="font-size:15px">No Credit Card Required|Give it a Shot</div >
        <br>
        <div class="ilogo">
          <table>
            <tr>
                <td>
                <img  alt ="i1"src= {tw}>
                </td><td>
                    <img  alt ="i2"src= {td}>
                </td><td>
                    <img  alt ="i3"src= {ta}>
                </td><td>
                    <img  alt ="i4"src= {tm}>
                </td>
                <td>
                    <img  alt ="i4"src= {tz}>
                </td>
            </tr>
          </table>
        </div>
</div>
<br><br>
<div class="centre">
    
        <div>
         <img class="timg" alt ="one" src={str1}>
        </div><div>
            <img  class="timg" alt ="on" src={m2}>
        </div><div>
            <img class="timg" alt ="o" src={m1}>
        </div><div>
            <img class="timg" alt ="ne" src={str2}>
        </div>
    
</div>
<style>
    .timg{
        width:100%;
        height:30px;
    }
    .centre{
        align-self: center;
        display: flex;
        
        margin-left: 290px;
        
    }
    .trns{
        color: rgb(231, 95, 11);
         
    }
    .para{
        align-content: center;
        margin-left: 60px;
        font-family: sans-serif;
    }
    #under{
        text-decoration-color: rgb(245, 125, 12);
        text-decoration-thickness: 3px; 
    }
    .button{
      background-color: rgb(237, 129, 34);
      color: white;
      border:none;
      min-height:min-content;
      transition: .3s;
      font-size: medium;
      padding-left: 1.5rem;
      padding-right: 1.5rem;
    }
    .button:hover{
        background-color: rgb(30, 30, 30);
        transition: cubic-bezier(0.165, 0.84, 0.44, 1);
        cursor: pointer;
    }
    
</style>
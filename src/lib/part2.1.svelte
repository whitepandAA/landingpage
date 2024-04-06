<script>
    let get=false;
    let getline=()=>{
     get=true;
    }
    let goline =()=>{
        get=false;
    }
</script>
<main class="main">
    <div class="head"><h1 class="heading">
        You'll Never Know Unless You <u id="line">Try Email Verifier!</u><br><br>
        <input style="height:30px; font:message-box;border-color:orange;"placeholder="test@email.com"><button class="btn">VALIDATE</button>
    </h1>
<div class="hov{get?"line":" "} line" on:mouseover={getline} on:mouseout={goline} >Try Email Finder|Try Prospect Finder</div>

</main>
<style>.btn{
        border-radius: 0;
    font-size: 15px;
    font-weight: 700;
    height: 40px;
    letter-spacing: .2px;
    padding: 6px 25px;
    background-color: rgb(222, 142, 14);
    border-color: rgb(222, 142, 14);
    
   
}
.hovline{
    text-decoration: underline;
    text-decoration-color:rgb(205, 99, 6) ;
}
.heading{
        text-align: center;
        
        padding-top: 15px;
        
  }.line{
    padding-left:224px;
  }
 .head{
        padding-left: 224px;
       
 }
 #line{
    text-decoration-color: rgb(245, 125, 12);
        text-decoration-thickness: 3px;
 }
</style>
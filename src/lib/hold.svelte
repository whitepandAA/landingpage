<script>
    import B2b from "./conent/b2b.svelte"
    import Linkedin from "./conent/capture.svelte";
    import Capture from "./conent/linkedi.svelte"
    import Verify from "./conent/verify.svelte";
    let page =B2b;
    let one=false
    let two=false 
    let three=false 
    let four=false
</script>
<main>
    <h1 style="text-align:center">
      Do it all with ClearOut
    </h1>
    <br>
    <br>
<div class="hold">
    <button id ="button"class="b2b {one?"line":""}" on:click={()=>{
       one=true
       two=false
       three=false
       four=false
       return page=B2b 
        
    }}>Find B2B Mails</button>
    <button id="button"class="linkedin {two?"line":""}"on:click={()=>{
        two=true 
        one=false
        three=false
        four=false
        return page=Linkedin
    }}>Get Linkedin Leads</button>
    <button id="button" class="capture {three?"line":""}" on:click={()=>{
        three=true 
        one=false
        two=false
        four=false
        return page=Capture
    }}>Verify at Capture</button>
    <button id="button"class="veify {four?"line":""}" on:click={()=>{
        four=true
        one=false
        two=false
        three=false
        page=Verify
    }}>Bulk Email validation</button>
</div><br>
<div class=other><svelte:component this={page}/></div>

</main>
<style>
    .other{
        background-color: rgb(247, 233, 222);
        margin-left: 120px;
        margin-right: 120px;
        font-family: sans-serif;
        color: rgb(147, 144, 144);
    }
    .hold{
        display: flex;
        justify-content: space-evenly;
    }
    #button{
        border:none;
   background-color:transparent;
   outline:none;
   font-size: large;
    }
    .line{
     text-decoration: underline;
     text-decoration-color:rgb(224, 118, 5) ;
    }
</style>
<script>
    // @ts-ignore
    import Subpart from "../lib/part2.1.svelte"
    import one from "../assets/tab3/adobe.webp"
    import two from "../assets/tab3/inmobi.webp"
    import three from "../assets/tab3/adobe.webp"
    import four from "../assets/tab3/chargebee.webp"
    import five from "../assets/tab3/truecaller.webp"
</script>
<main>
    <div class="cl1">
        <h1 style="text-align: center; margin-top:15px">Trusted by business of all sizes WorldWide </h1>
        <p style="text-align: center;">Our solutions have been adopted by <span class="number" style="color:white"><strong>40000+</strong></span> businesses worldwide to efficiently identify and qualify leads in real-time and in bulk.</p>
        <br>
       
        <table align="center" ><tr>
            <td>
            <img alt ="one" src={one}>
            </td><td>
                <img alt ="teo" src={two}>
            </td>
            <td>
                <img alt ="three" src={three}>
            </td>
            <td>
                <img alt ="four" src={four}>
            </td><td>
                <img alt ="five" src={five}>
            </td>
        </tr></table>
        <div class="sepbox"><Subpart/></div>
    </div>
    
</main>
<style>
    tr,td{
        padding: 49px;
    }
    .number{
        background-color: rgb(62, 61, 61);
        border-radius: 15px;
        padding-left: 4px;
        padding-right: 4px;
    }
    .cl1{
        padding-top: 30px;
       height: 517px;
       width: 1500px; 
       background-color: rgb(250, 246, 246);
       font-family: sans-serif;
       color: rgb(74, 72, 72);
    }
    .sepbox{
        display: flex;
        
        margin-left:117px;
        height: 243.6px;
        width:1270px;
        background-color: rgb(193, 189, 189);
    }
</style>
<script>
   
 let info=[{
        col:"rgba(196, 147, 255, 0.14)",
        img:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbgdTtu8hN7sIIQtNRBH1g2THSseDuO5UdfA&usqp=CAU" ,
        heading:"Accurate Result",
        subheading:"The more you know, the better.<br> Our 98%+ accurate results uphold your sender reputation."
    },
    {
        col:"rgba(245, 124, 0, 0.11)",
        img:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLML1Z4kjlUDqMANzMi8DuKxZDgL5r82XRaw&usqp=CAU",
        heading:"Cost-Effective",
        subheading:"Relax, we've scaled exactly for your wallet.<br> Transparent pricing, every penny counts!"    
    },
    {col:"rgba(147, 190, 255, 0.14)",
        img:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQm6ZN81E1p18e3g71A0IKDncaXO5NACbj-wg&usqp=CAU",
        heading:"Quick Turnaround",
        subheading:"From typos to mail server verification, we're the fastest. <br>Your time is worth it."},
    {col:"rgba(147, 255, 218, 0.14)",
        img:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR02y0a7r56Si4674jp_sGPsp_73qhwUXk7CA&usqp=CAU",
        heading:"Guaranteed Deliverability",
        subheading:"Best practices & guaranteed email deliverability rates to back our<br> verification results."}]
</script>

<main>
    <div class="master">
        {#each info as da }
        <div class='crd' style="background-color:{da.col};">
            <img  class="ig"alt="img1" src="{da.img}">
            <p style="padding-left:20px">{da.heading}</p>
            <p style="text-align:centre">{@html da.subheading}</p>
        </div>
        {/each}
    </div>
   
    
</main>
<style>
    .ig{
        height:120px;
        width:120px;
        padding-left:38px ;
    }
   .master{
    display: flex;
    justify-content: space-evenly;
    margin-left: 144px;
    margin-right:201px;
   } 
.crd{
   margin-right:10px;
   margin-left: 10px;
    height: 291px;
    width: 210px;
}
</style>
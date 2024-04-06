<script>
    let info=[{
        col:"rgba(196, 147, 255, 0.14)",
       
        heading:"Data  Encryption",
        subheading:"We take your data security seriously. That's why we use 256-bit SSL encryption to secure the entire transmission and safeguard your information."
    },
    {
        col:"rgba(245, 124, 0, 0.11)",
        
        heading:"Data Retention",
        subheading:"We safeguard your data and offer flexible retention options for your email list, with default retention of 30 days or customized retention periods upon request."    
    },
    {col:"rgba(147, 190, 255, 0.14)",
       
        heading:"Compliance",
        subheading:"We adhere to the highest standards of data security, including compliance with GDPR, SOC 2 Type 2 and ISO norms, to ensure that your customer data is always protected."},
    ]

    
</script>
<main>
    <h1 style="text-align: center;">Data Security</h1>
    <div class="master">
        
        {#each info as da }
        <div class='crd' style="background-color:{da.col};">
            
            <p style="padding-left:20px">{da.heading}</p>
            <p style="text-align:centre">{ da.subheading}</p>
        </div>
        {/each}
    </div>
   
    
</main>
<style>
    
   .master{

    display: flex;
    justify-content: space-evenly;
    margin-left: 144px;
    margin-right:201px;
   } 
.crd{
    
    text-align: center;
   margin-right: 4px;;
   margin-left: 69px;
    height: 228px;
    width: 198px;
    padding-left: 40px;
    padding-right:63px;
    border-radius: 26px;
}
</style>
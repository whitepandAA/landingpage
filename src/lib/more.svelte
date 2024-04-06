<script>
    import ef from "../assets/hold/clearout_email_finder.webp"
    import ev from "../assets/hold/clearout_ev.webp"
    import li from "../assets/hold/clearout_linkedin_search.webp"
    import prospect from "../assets/hold/clearout_prospecting.webp"
</script>
<main style="font-family:Inter, sans-serif;">
    <div class="master">
        <div class ="one">
            <div class="on">
                <img  class="img" alt="xt" src={prospect}>
            </div>
            <div class="txt">
                <h1>Prospecting & Enrichment</h1><br>
                <p><i> LinkedIn Chrome Extension to capture high-profile leads</i></p>
                <ul>
                    <li>
                        Clearout's LinkedIn Chrome Extension enables you to quickly identify potential prospects and capture verified business email addresses within minutes.
                    </li>
                    <li>
                        In addition to email addresses, the extension allows you to enrich data for single or multiple prospects, finding valid contact numbers with ease.
                    </li>
                    <li>
                        This feature streamlines your lead generation process and enhances efficiency, saving you time and enabling you to focus on converting leads into customers.
                    </li>
                </ul>
                <button class="bton">
                    Explore
                </button>
            </div>
        </div>
        <br>
        <div class ="one">
            
            <div class="txt">
                <h1>Email Finder</h1><br>
                <p><i>Capture email addresses with just a name!</i></p>
                <ul>
                    <li>
                        The Email Finder offers multiple search options like domain search, company name search, and name plus domain search, giving you more control. 
                    </li>
                    <li>
                        The API integration seamlessly fits into your workflow, allowing you to find emails individually or in bulk. 
                    </li>
                    <li>
                        With the confidence scoring system, you get the most accurate and up-to-date email addresses, leading to effective email marketing campaigns and business growth.
                    </li>
                <li>
                    Trust our email finder to elevate your lead generation efforts and take your business to the next level.

                </li>

                </ul>
                
                <button class="bton">
                    Explore
                </button>
            </div>
            <div class="on">
                <img  class="img" alt="xt" src={ef}>
            </div>
        </div>
        <br>
        <div class ="one">
            <div class="on">
                <img  class="img" alt="xt" src={ev}>
            </div>
            <div class="txt">
                <h1>Email Validation</h1><br>
                <p><i> Verify any email addresses with utmost accuracy!</i></p>
                <ul>
                    <li>
                        Clearout's versatile email verifier tool offers both real-time and bulk validation options to suit your needs
                    </li>
                    <li>
                        You can download the verified results and append them to your original file, making it easy to keep your database up-to-date
                    </li>
                    <li>
                        For smaller lists, our quick email verifier allows you to copy and paste email addresses & get instant results

                    </li>
                        
                </ul>
                <button class="bton">
                    Explore
                </button>
            </div>
        </div>
    </div>
</main>
<style>
    .txt{
        margin-left:43px;
    margin-right:39px;   
 }
    .img{
        padding-left: 141px;
        height: 380px;
        width:480px;
    }
.bton{
    background-color:transparent;
   outline:none;
   font-size: large;
}
.bton:hover{
    background-color: #212529;
    color: white; 
}
    .one{
        display: flex;
        justify-content: space-evenly;
        margin-left:72px;
        margin-right:180px
    }
</style>
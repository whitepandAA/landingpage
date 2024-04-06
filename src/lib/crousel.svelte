<script>import Carousel from "../../node_modules/svelte-carousel"
import s1 from "../assets/crfolder/Screenshot (125).png"
import s2 from "../assets/crfolder/Screenshot (126).png"
import s3 from '../assets/crfolder/Screenshot (127).png'
import s4 from '../assets/crfolder/Screenshot (128).png' 
const imginfo=[s1,s2,s3,s4];

</script>
<main>
    <div class="hero">
        <Carousel
                autoplay 
                autoplayDuration={3000}
            >
              {#each imginfo as ig }
                <img src={ig} alt=one>
              {/each}  
        </Carousel>
    </div>
</main>

<script>
  import Navbar from "./lib/navbar.svelte";
  import Subheader from "./lib/subheader.svelte";
  import Part2 from "./lib/part2.svelte";
  import Hold from "./lib/hold.svelte";
  import Cards from "./lib/cards.svelte";
  import More from "./lib/more.svelte";
  import Awards from "./lib/awards.svelte";
  
  import Ds from "./lib/ds.svelte";
  import Api from "./lib/api.svelte";
  import Createfree from "./lib/createfree.svelte";
</script>


<main class="main" style="font-family:sans-serif">
  <div class="same"><Navbar/>
    <Subheader/></div><br>
    <Part2/>
    <br>
    
    <Hold/>
    <br>
    <br>
    
    <h1 style="text-align: center;">Features That Define Our Actions</h1>
    <br><br>
  <Cards/><br>
  <br>
<More/>
<Awards/>
<br>
<Ds/>
<br>
<Api />
<Createfree/>
  <h1>3</h1> <h1>3</h1> <h1>3</h1> <h1>3</h1> <h1>3</h1> <h1>3</h1> <h1>3</h1> <h1>3</h1>
</main>

<style>
  .same{
    background: rgb(255,237,168);
background: linear-gradient(90deg, rgba(255,237,168,1) 0%, rgba(255,255,255,1) 100%);
  }
</style>
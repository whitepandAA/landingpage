<script>
    import logo from "../assets/images/logo.png"
    let isNavbarSticky = false; 
    function handleScroll() {
    isNavbarSticky = window.scrollY > 0;
  }
  window.addEventListener('scroll', handleScroll);
</script>

<div class="main">
   <div class="nav {isNavbarSticky ? 'sticky' : ''}">
    <span class="img"><img  alt ="img "src={logo}></span>
    <span class="list">
      
        <span class="item"><h4>Products</h4></span>
        <span class="item"><h4>Resources</h4></span>
        <span class="item"><h4>Pricing</h4></span>  
        <span class="item"><h4>Integration</h4></span>
        <span class="item"><h4>Enterprises</h4></span>
        <span class="item"><h4>Login</h4></span>
      
    </span>
   </div>
  
</div>
<style>
.img{
    margin-left:90px;
}
 .nav{
    
    display: flex;
    justify-content: space-between;
    position: fixed;
    top: 0px;
    
    width: 100%;
    
     z-index: 0; background: rgb(255,237,168);
background: linear-gradient(90deg, rgba(255,237,168,1) 0%, rgba(255,255,255,1) 100%);
     
 }
 .nav.sticky {
 
   box-shadow: 0 42px 100px rgba(0, 0, 0, 0.1); 
 }
 .list{
    display: flex;
    flex-wrap: wrap;
   
 }
 .item{
   
    margin-left: 30px;
    margin-right: 30px;
    color: rgb(67, 66, 66);
    font-size: large;
    font-family: 'Times New Roman', Times, serif;
 }
 
</style>
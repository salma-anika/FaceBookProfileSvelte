<script>
    import "../app.css";
    import Navbar from '../routes/navbar/+page.svelte';
    import Intro from '../routes/intro/+page.svelte';
    import Tab from '../routes/tab/+page.svelte'
    import Tabs from '../routes/tabs/+page.svelte'
    import Tablist from '../routes/tablist/+page.svelte'
    import  Tabpanel from '../routes/tabpanel/+page.svelte'
    import More from "../icons/more.svelte";
  </script>
  <Navbar/>
  <Intro/>
 
   

  <slot />
<script>
    import "../app.css";
    import Navbar from '../routes/navbar/+page.svelte';
    import Intro from '../routes/intro/+page.svelte';
    import Tab from '../routes/tab/+page.svelte'
  </script>
  <Navbar/>
  <Intro/>
<Tab/>
  <slot />
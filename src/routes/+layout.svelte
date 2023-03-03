<script>
    import "../app.css";
    import Navbar from '../routes/navbar/+page.svelte';
    import Intro from '../routes/intro/+page.svelte';
    import Timelinepost from '../routes/timelinepost/+page.svelte'
  </script>
  <Navbar/>
  <Intro/>
<Timelinepost/>
  <slot />
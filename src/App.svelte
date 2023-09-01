<script>
  import { Route, Router } from 'svelte-routing';
  import Navbar from './components/Navbar.svelte';
  import Chart from "./pages/Chart.svelte";
  import Layout from "./pages/Layout.svelte";
  import Map from "./pages/Map.svelte";
</script>
<Router>
  <Navbar/>
  <Route path="/layout" component={Layout}/>
  <Route path="/chart" component={Chart}/>
  <Route path="/map" component={Map}/>
</Router>


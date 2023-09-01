<script>
  import { countryDataStore } from "../store/store";

  const mostPopulatedCountry = $countryDataStore.sort((a, b) => b.population - a.population);
  console.log(mostPopulatedCountry.slice(0, 10));
</script>

<h1 class="text-3xl underline text-bold-">I am a Map Page</h1>

<style>

</style>
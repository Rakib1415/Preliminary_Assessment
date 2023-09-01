<script>
    import { countryDataStore } from "../store/store";

    const getCountryData = async() => {
        const res = await fetch('https://restcountries.com/v3.1/all');
        const data = await res.json();
        countryDataStore.set(data);
    }
    getCountryData();
  
</script>

<h1 class="text-3xl underline text-bold-">I am a Chart Page</h1>

<style>

</style>

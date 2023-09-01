<script>
    import { Link } from 'svelte-routing';
</script>

<div class="h-8 bg-slate-300" />
<nav class="sticky top-0 z-50 bg-black">
  <div class="container px-6 py-3 ">
    <div class="flex items-center justify-between">
        <div>
            <Link
              class="text-2xl hover:text-orange-500 font-bold text-white transition-colors duration-300 transform lg:text-3xl"
              to="/layout"
            >
            Preliminary Assessment - Junior Frontend Engineer
            </Link>
          </div>
        <div class="flex items-center space-x-5 justify-end">
            <div>
                <Link let:active
                  class="text-xl hover:text-orange-500 font-bold text-white transition-colors duration-300 transform lg:text-2xl"
                  to="/layout"
                >
                
                <span class={active ? "text-orange-500": "text-white"}>Layout</span>
                </Link>
              </div>
              <div>
                <Link let:active
                  class="text-xl hover:text-orange-500 font-bold text-white transition-colors duration-300 transform lg:text-2xl"
                  to="/chart"
                >
                <span class={active ? "text-orange-500": "text-white"}>Chart</span>
                
        
                </Link>
              </div>
              <div>
                <Link let:active
                  class="text-xl  hover:text-orange-500 font-bold text-white transition-colors duration-300 transform lg:text-2xl"
                  to="/map"
                >
                <span class={active ? "text-orange-500": "text-white"}>Map</span>
                
                </Link>
              </div>
        </div>
    </div>
  </div>
</nav>
<div class="h-8 bg-slate-300" />

<style></style>
<script lang="ts">
	import '../app.postcss';
	import { AppShell, LightSwitch } from '@skeletonlabs/skeleton';
</script>

<AppShell>
  <slot />

  <div class="p-4 rounded-sm mt-8">
    <div class="mt-8 flex flex-col md:flex-row justify-center items-center md:space-x-4">
        <div></div>
        <div class="btn-group variant-ghost-surface">
          <a href="/about"> 
            <button class="w-full md:w-auto font-[var(--theme-font-family-heading)]">ABOUT</button>
          </a>
            <a href="/mint"> 
            <button class="w-full md:w-auto">MINT</button>
          </a>

          <a href="https://www.etsy.com/shop/tokeneyeslabs"> 
            <button class="w-full md:w-auto">SHOP</button>
            </a>
        </div>
    </div>
</div>



  <div class="mt-12 flex justify-center items-center space-x-4">
  </div>

  <svelte:fragment slot="pageFooter">
	<div class="mt-12 flex justify-center items-center space-x-4">

    <a
				href="https://discord.com/invite/TwVywVhpfp"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
	  <img src="../icons/discord.png" alt="xrp" class="w-15 h-12" />
    </a>

    <a
				href="https://opensea.io/collection/tokeneyes"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
	  <img src="../icons/opensea.png" alt="xrp" class="w-15 h-10" />
    </a>


    <a
				href="https://twitter.com/tokeneyeslabs"
				target="_blank"
				rel="noreferrer"
				class="flex items-center justify-center"
			>
	  <img src="../icons/x.png" alt="xrp" class="w-15 h-10" />
    </a>
	</div>
  </svelte:fragment>
  
</AppShell>

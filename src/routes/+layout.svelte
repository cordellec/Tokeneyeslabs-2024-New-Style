<script lang="ts">
	import '../app.postcss';
	import { AppShell, LightSwitch } from '@skeletonlabs/skeleton';
</script>

<AppShell>
  <slot />

  <div class="p-4 rounded-sm mt-16">
    <div class="mt-8 flex justify-center items-center space-x-4">
      <div></div>
      <div class="btn-group variant-ghost-surface text-center text-black">
        <button class="w-full">About</button>
        <button class="w-full">Mint</button>
        <button class="w-full"><LightSwitch></LightSwitch></button>
      </div>
    </div>
  </div>


  <div class="mt-12 flex justify-center items-center space-x-4">
  </div>

  <svelte:fragment slot="pageFooter">
	<div class="mt-12 flex justify-center items-center space-x-4">
	  <img src="../icons/discord.png" alt="xrp" class="w-15 h-12" />
	  <img src="../icons/opensea.png" alt="xrp" class="w-15 h-10" />
	  <img src="../icons/x.png" alt="xrp" class="w-15 h-10" />
	  <img src="../icons/etsy.png" alt="xrp" class="w-15 h-10" />
	</div>
  </svelte:fragment>
  
</AppShell>

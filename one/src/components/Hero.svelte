<script>

  import SectionWrapper from "./SectionWraper.svelte";
  import { AppBar } from '@skeletonlabs/skeleton';


</script>


<SectionWrapper>

  
  <AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
  	<svelte:fragment slot="lead">(icon)</svelte:fragment>
  	(title)
  	<svelte:fragment slot="trail">(actions)</svelte:fragment>
  </AppBar>


</SectionWrapper>

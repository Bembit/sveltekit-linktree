<script>
    export let icon = 'default';
    export let url = 'foo';
    export let title = 'some cool title';
</script>

<a target="_blank" href={url} class="mx-auto mb-2 stack w-full max-w-md text-center bg-secondary flex justify-center items-center p-4 not-prose no-underline">
  <!-- <img src={`/${icon}.png`} alt={icon} width="32" height="32" class="w-8" /> -->
  <span class="text-lg text-white font-bold">{title}</span>
</a>
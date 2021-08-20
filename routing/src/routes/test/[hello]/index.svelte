<script lang="ts" context="module">
  export const load = (input) => ({
    props: {
      ...(input.page.params || {}),
    },
  });
</script>

<script lang="ts">
  export let hello!: string;
</script>

<h1>{hello}</h1>

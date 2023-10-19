<script>
  import { onMount } from "svelte"

  let modalDialog = null;

  onMount(() => modalDialog = document.getElementById("modal_dialog"))

  const showModalClick = (isActive = true) => modalDialog[isActive ? "showModal" : "close"]()
</script>

<!-- Modal ---------------------------------------------------------- -->
<h3 id="MODAL">Modal</h3>

<button on:click={() => showModalClick(true)}>Open modal</button>
<dialog id="modal_dialog">
  <p>Pack my box with five dozen liquor jugs.</p>
  <button on:click={() => showModalClick(false)}>Close modal</button>
</dialog>

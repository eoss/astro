<script>
  export let title = 'Welcome to My Website';
  export let description = 'This is a one-page website built with Astro and Svelte!';
</script>

<style>
  section {
    text-align: center;
    padding: 50px;
    background-color: #f4f4f4;
  }

  h1 {
    font-size: 3em;
    color: #333;
  }

  p {
    font-size: 1.5em;
    color: #666;
  }

  button {
    padding: 10px 20px;
    font-size: 1em;
    background-color: #007bff;
    color: white;
    border: none;
    cursor: pointer;
  }

  button:hover {
    background-color: #0056b3;
  }
</style>

<section>
  <h1>{title}</h1>
  <p>{description}</p>
  <button>Click Me</button>
</section>

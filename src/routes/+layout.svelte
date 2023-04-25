<script>
   import "../app.css";
 </script>

<main class="max-w-screen-lg mx-auto px-4">
   <header class="py-4 flex justify-between">
      SvelteKitTest
      <nav>
         <a href="/" class="underline">Home</a>
         <a href="/about" class="underline">About</a>
      </nav>
   </header>
   <slot />
</main>
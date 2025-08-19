<script>
  export let health;
</script>

<main class="flex flex-col items-center justify-center min-h-screen bg-gradient-to-br from-blue-800 to-green-400">
  <h1 class="text-5xl font-bold text-white mb-6">Ultimate League Soccer (ULS)</h1>
  <p class="text-lg text-white mb-2">Create your club, build your squad, and compete in leagues!</p>
  <a href="/auth" class="mt-4 px-6 py-2 bg-white text-blue-800 rounded shadow hover:bg-blue-100">Get Started</a>
  <div class="mt-12 text-white opacity-70">API Health: {health ? '✅' : '❌'}</div>
</main>
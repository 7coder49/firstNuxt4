<script lang="ts" setup>
  const router = useRouter();
  const goToNextPage = () => {
    router.push('/dynamics/123')
  }
</script>

<template>
  <div id="home-container" style="display: flex; flex-direction: column; align-items: center; justify-content: center; background: #f8f9fa;">
    <div style="width: 80vw; max-width: 900px;">
      <h1 style="margin-bottom: 2rem;">Full Screen Table</h1>
      <table style="border-collapse: collapse; background: #fff; box-shadow: 0 2px 8px rgba(0,0,0,0.05);"
      class="w-full">
        <thead style="background: #333; color: #fff;">
          <tr>
            <th style="padding: 1rem; border: 1px solid #ddd;">Name</th>
            <th style="padding: 1rem; border: 1px solid #ddd;">Age</th>
            <th style="padding: 1rem; border: 1px solid #ddd;">Country</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td style="padding: 1rem; border: 1px solid #ddd;">Alice</td>
            <td style="padding: 1rem; border: 1px solid #ddd;">24</td>
            <td style="padding: 1rem; border: 1px solid #ddd;">USA</td>
          </tr>
          <tr>
            <td style="padding: 1rem; border: 1px solid #ddd;">Bob</td>
            <td style="padding: 1rem; border: 1px solid #ddd;">30</td>
            <td style="padding: 1rem; border: 1px solid #ddd;">UK</td>
          </tr>
          <tr>
            <td style="padding: 1rem; border: 1px solid #ddd;">Charlie</td>
            <td style="padding: 1rem; border: 1px solid #ddd;">28</td>
            <td style="padding: 1rem; border: 1px solid #ddd;">Canada</td>
          </tr>
        </tbody>
      </table>
      <div class="w-full py-10 h-10 flex items-center justify-end">
        <button
          @click="goToNextPage"
          class="border-b border-gray-200 px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 focus:outline-none focus:ring-2
          focus:ring-blue-400"
        >
          Next Page
        </button>
      </div>
    </div>
  </div>
</template>
<style lang="scss">

</style>
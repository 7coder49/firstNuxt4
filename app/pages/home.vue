<template>
  <div style="display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; width: 100vw; background: #f8f9fa;">
    <h1 style="margin-bottom: 2rem;">Full Screen Table</h1>
    <table style="width: 80vw; max-width: 900px; border-collapse: collapse; background: #fff; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
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
  </div>
</template>
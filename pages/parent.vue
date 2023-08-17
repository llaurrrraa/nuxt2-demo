<template>
  <div class="container">
    <h1>I am the parent view</h1>
    <nav>
      <ul>
        <li>
          <NuxtLink to="/parent">index</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/parent/child">Child1</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/parent/child2">Child2</NuxtLink>
        </li>
      </ul>
    </nav>
    <NuxtChild></NuxtChild>
  </div>
</template>
<style></style>

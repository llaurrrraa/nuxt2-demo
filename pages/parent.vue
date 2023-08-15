<template>
  <div class="parent-container">
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
<style scoped>
.parent-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
h1 {
  color: #e6a23c;
}
ul {
  list-style: none;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0;
}
li {
  margin: 0 0.5rem;
  padding: 0.25rem;
  font-size: 1rem;
}
</style>

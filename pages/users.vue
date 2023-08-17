<template>
  <div class="container">
    <h1>This is users container</h1>
    <nav>
      <ul>
        <li>
          <NuxtLink to="/users">index</NuxtLink>
        </li>
        <li v-for="(n, index) in 10" :key="index">
          <NuxtLink :to="{ name: 'users-id', params: { id: n } }"
            >users{{ n }}</NuxtLink
          >
        </li>
      </ul>
    </nav>
    <NuxtChild />
  </div>
</template>

<template>
  <div>
    <main v-if="$route.params.slug">
      <h1 v-text="'Blog ' + $route.params.slug"></h1>
    </main>

    <main v-else>
      <h1>List blog there are no slug here</h1>
    </main>
  </div>
</template>

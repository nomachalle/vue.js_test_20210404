<template>
  <div>
    <ul>
      <li>
        <router-link :to="{name: 'Member', prams: { id: 1 }}">
          1へ進む
        </router-link>
      </li>
      <li>
        <router-link :to="{name: 'Member', prams: { id: 2 }}">
          2へ進む
        </router-link>
      </li>
      <li>
        <router-link :to="{name: 'Member', prams: { id: 3 }}">
          3へ進む
        </router-link>
      </li>
    </ul>
  </div>
</template>

<script>
</script>

<style scoped>
ul {
  padding: 0px;
}
li {
  list-style: none;
}
</style>
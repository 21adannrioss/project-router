<template>
  <div>
    <nav>
      <RouterLink to="/">🏠 inici</RouterLink> |
      <RouterLink to="/frameworks">⚙️ Frameworks</RouterLink>
    </nav>
    <hr />
    <RouterView />
  </div>
</template>


<style>
nav {
  background: #e0eafc;
  padding: 10px;
  
}
</style>
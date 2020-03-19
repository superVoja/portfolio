<template>
  <header>
    <div class="container">
      <div class="brand">
        <nuxt-link to="/">vojislav.</nuxt-link>
      </div>
      <nav>
        <ul>
          <li>
            <nuxt-link to="/projects">projects</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">about</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact">contact</nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
<style lang="scss" scoped>
.container {
  width: 100%;
  display: flex;

  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  border-bottom: 1px solid $primary-color;
}
.brand {
  flex-basis: 25%;
  max-width: 25%;
  display: block;
  padding: 1.2rem 0;

  a {
    color: #000;
    text-decoration: none;
  }
}
nav {
  flex-basis: 75%;
  max-width: 75%;
  ul {
    display: flex;
    justify-content: flex-end;
    text-align: right;

    li {
      list-style: none;
      padding: 0 1.2rem;
    }
    a {
      display: block;

      text-decoration: none;
      color: $primary-text;
      text-transform: lowercase;
    }
  }
}
</style>
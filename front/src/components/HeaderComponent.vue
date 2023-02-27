<script setup></script>

<template>
  <header class="header">
    <div class="container">
      <img class="header_brand" src="" alt="" />

      <nav>
        <ul>
          <li><a href="#" class="active">Accueil</a></li>
          <li><a href="#" class="notification">Réviser</a></li>
          <li><a href="#">Live</a></li>
          <li><a href="#">Explorer</a></li>
          <li><a href="#">Tarifs</a></li>
        </ul>
      </nav>

      <ul class="ml-auto">
        <li><a href="#">Aide</a></li>
        <li><a href="#" class="caret">user.name</a></li>
      </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.header {
  height: 60px;
  border-bottom: 1px solid red;

  &::after {
    box-shadow: 0 2px 2px 0 #284b7c14;
    content: "";
    height: 1px;
    left: 0;
    position: absolute;
    top: calc(3.75em - 1px);
    width: 100%;
  }

  &_brand {
    width: 92px;
    margin-right: 30px;
  }

  .container {
    padding: 0;
    height: 100%;
    display: flex;
    align-items: center;
  }

  a.active {
    color: var(--color-text-active);
  }

  li {
    display: inline;
  }

  li:not(:last-child) {
    margin-right: 24px;
  }
}
</style>

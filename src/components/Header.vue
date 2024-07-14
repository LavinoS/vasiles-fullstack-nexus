<template>
  <header role="banner">
    <!--    <div class="logo"></div>-->
    <nav class="navigation" aria-label="Main navigation">
      <ul class="nav-list">
        <li class="nav-item">
          <NuxtLink to="#" exact-active-class="active">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="#about-section" exact-active-class="active"
            >About</NuxtLink
          >
        </li>
        <li class="nav-item">
          <NuxtLink
            scroll-behaviour="smooth"
            to="#skills-section"
            exact-active-class="active"
            >Skills</NuxtLink
          >
        </li>
        <li class="nav-item">
          <NuxtLink to="#projects-section" exact-active-class="active"
            >Projects</NuxtLink
          >
        </li>
      </ul>
    </nav>
    <!--    <button class="hire-button">-->
    <!--      <span> Hire me </span>-->
    <!--    </button>-->
  </header>
</template>

<script setup lang="ts"></script>

<style scoped lang="css">
.logo {
  width: 200px;
}

header {
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 10;
  color: var(--light-tertiary-color);
  background: var(--dark-tertiary-color);
  padding: 0 48px;
  display: flex;
  //justify-content: space-between;
  align-items: center;
  justify-content: center;
}

ul {
  display: flex;
}

li {
  text-transform: uppercase;
  font-weight: 600;
  font-size: 14px;
  letter-spacing: 1px;
  padding: 24px 48px;
}

.hire-button {
  background: var(--light-tertiary-color);
  color: var(--dark-primary-color);
  padding: 12px 24px;
  cursor: pointer;
  font-weight: 600;
  letter-spacing: 1px;
  appearance: none;
  text-transform: uppercase;
  width: 200px;
}
</style>

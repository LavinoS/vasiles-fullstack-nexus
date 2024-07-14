<template>
  <section>
    <div class="left-side">
      <h2 class="presentation-heading-1">Hello, I'm Vasile Mihalache!</h2>
      <h1 class="presentation-heading-2">
        I'm a Full-Stack Web Developer passionate about crafting impactful web
        experiences.
      </h1>
      <h3 class="presentation-heading-3">Code. Create. Innovate.</h3>
    </div>
    <div class="right-side">
      <img
        alt="photo"
        src="../assets/images/75740250-447a-4c4b-9e5d-9a1daabde1da.jpg"
      />
    </div>
    <div class="experience-banner">
      <div style="width: 40%; display: flex; gap: 24px">
        <div style="display: flex; gap: 12px; align-items: center">
          <h3 style="font-size: 64px">5</h3>
          <p style="max-width: 40%; font-size: 20px; line-height: 28px">
            YEARS OF EXPERIENCE
          </p>
        </div>
        <div style="display: flex; gap: 12px; align-items: center">
          <h3 style="font-size: 64px">9</h3>
          <p style="max-width: 50%; font-size: 20px; line-height: 28px">
            PROJECTS COMPLETED AROUND THE WORLD
          </p>
        </div>
      </div>
      <div style="width: 60%; display: flex; gap: 32px">
        <Icon name="logos:javascript" size="77px" />
        <Icon name="devicon:typescript" size="77px" />
        <Icon name="logos:react" size="77px" />
        <Icon name="devicon:nextjs" size="77px" />
        <Icon name="devicon:vuejs" size="77px" />
        <Icon name="logos:nuxt-icon" size="77px" />
        <Icon name="logos:nodejs-icon" size="77px" />
        <Icon name="logos:postgresql" size="77px" />
        <Icon name="logos:mongodb-icon" size="77px" />
        <Icon name="vscode-icons:file-type-astro" size="77px" />
        <Icon name="vscode-icons:file-type-graphql" size="77px" />
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="css">
section {
  background: var(--dark-secondary-color);
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(8, 1fr);
}

.presentation-heading-1 {
  color: var(--light-tertiary-color);
  font-size: 32px;
  margin-bottom: 16px;
}

.presentation-heading-2 {
  color: var(--light-primary-color);
  font-size: 48px;
  margin-bottom: 16px;
}

.presentation-heading-3 {
  color: var(--light-tertiary-color);
  font-size: 28px;
  text-transform: uppercase;
  font-weight: 900;
  letter-spacing: 1px;
}

.left-side {
  display: flex;
  justify-content: center;
  align-items: start;
  flex-direction: column;
  padding: 48px 64px;
  grid-area: 1 / 1 / 8 / 2;
}

.right-side {
  height: 100%;
  grid-area: 1 / 2 / 8 / 3;
}

.right-side img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.experience-banner {
  background: var(--dark-primary-color);
  grid-area: 8 / 1 / 9 / 3;
  color: #fff;
  display: flex;
  padding: 24px 64px;
}
</style>

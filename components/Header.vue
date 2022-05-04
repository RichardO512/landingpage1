<template>
  <section>
    <!-- toggle button -->
    <label class="switch">
      <input type="checkbox" class="checkbox" />
      <span class="toggle-thumb">
        <p>New feature</p>
        <p>Check out the team dashboard</p>
      </span>
    </label>

    <!-- text content -->

    <b-container fluid>
      <!-- Content here -->
      <h1>Beautiful analytics to grow smarter</h1>
      <p>
        Powerful, self-serve product and growth analytics to help you convert,
        engage,<br />
        and retain more users. Trusted by over 4,000 startups.
      </p>
    </b-container>

    <!-- button -->
    <div class="d-grid gap-2 d-md-block">
      <button class="btn btn-1 btn-lg" type="button">
        <span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-play-circle"
            viewBox="0 0 16 16"
          >
            <path
              d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
            />
            <path
              d="M6.271 5.055a.5.5 0 0 1 .52.038l3.5 2.5a.5.5 0 0 1 0 .814l-3.5 2.5A.5.5 0 0 1 6 10.5v-5a.5.5 0 0 1 .271-.445z"
            />
          </svg>
          Demo
        </span>
      </button>
      <button class="btn btn-2 btn-lg" type="button">Sign up</button>
    </div>

    <div class="img-section">
      <img
        src="../assets/ScreenMockup.png"
        alt=""
        class="rounded float-start img-fluid"
      />
    </div>

    <div class="end-section">
      <p>Join 4,000+ companies already growing</p>
    </div>
    <!-- Logos -->

    <b-container class="logo container text-center img-fluid">
      <b-row sm="2" lg="5">
        <b-col> <img src="../assets/Layer.png" /></b-col>
        <b-col><img src="../assets/Sisyphus.png" /> </b-col>
        <b-col><img src="../assets/Circooles.png" /> </b-col>
        <b-col><img src="../assets/Catalog.png" /> </b-col>
        <b-col><img src="../assets/Qoutient.png" /></b-col>
        <b-col><img src="../assets/Hourglass.png" /></b-col>
      </b-row>
    </b-container>
  </section>
</template>
<script>
export default {
  name: 'HeaderSection',
}
</script>
<style scoped src="../style/Header.css"></style>

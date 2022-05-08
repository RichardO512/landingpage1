<template>
  <section>
    <!-- toggle button -->

    <!-- text content -->

    <div
      class="d-flex flex-column justify-content-center align-items-center top"
    >
      <h1 class="my-2 mx-auto text-center">
        Beautiful analytics to grow smarter
      </h1>
      <p class="my-4 mx-auto text-center">
        Powerful, self-serve product and growth analytics to help you convert,
        engage, and retain more users. Trusted by over 4,000 startups.
      </p>
    </div>
    <!-- <div class="d-block col top text-center mx-auto px-5">
      <div class="row-sm-9 row-sm-7 mx-auto">
        <h1 class="my-2 mx-auto text-center">
          Beautiful analytics to grow smarter
        </h1>
      </div>
      <div class="row-xs-3 row-md-5 mx-auto">
        <p class="my-4 mx-auto">
          Powerful, self-serve product and growth analytics to help you convert,
          engage,<br />
          and retain more users. Trusted by over 4,000 startups.
        </p>
      </div>
    </div> -->
    <!-- button -->
    <div class="d-grid gap-2 d-md-block mx-auto">
      <button class="btn btn-1 btn-lg mx-auto" type="button">
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
      <button class="btn btn-2 btn-lg mx-auto" type="button">Sign up</button>
    </div>
  </section>
</template>
<script>
export default {
  name: 'HeaderSection',
}
</script>
<style scoped src="../style/Header.css"></style>

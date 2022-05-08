<template>
  <section>
    <div class="container container1 mt-3">
      <div
        class="d-flex flex-column justify-content-center align-items-center mb-3"
      >
        <div class="text-center h1">
          <h1>Beautiful analytics to grow smarter</h1>
          <!-- </div>
          <div> -->
          <p class="text-center p-tag">
            Powerful, self-serve product and growth analytics to help you
            convert, engage, and retain more users. Trusted by over 4,000
            startups.
          </p>
        </div>
      </div>
    </div>
    <div
      class="container container1 btn d-flex flex-grow-1 justify-content-center align-items-center"
    >
      <div class="d-grid gap-2 mx-auto">
        <button
          class="btn btn0 btn-primary btn-outline-dark btn-light"
          type="button"
        >
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
        <button class="btn btn1" type="button">Sign up</button>
      </div>
    </div>
    <div class="container img1">
      <img src="../assets/Content1.png" class="img-fluid" alt="..." />
    </div>
    <div class="container container1 b-text text-center">
      <p class="bottom">Join 4,000+ companies already growing</p>
    </div>
    <!--  -->
    <!-- <div
      class="d-flex container justify-content-center align-items-center logo text-center img-fluid"
    >
      <div class="one"><img src="../assets/Layer.png" /></div>
      <div class="two"><img src="../assets/Sisyphus.png" /></div>
      <div class="three"><img src="../assets/Circooles.png" /></div>

      <div class="five"><img src="../assets/Catalog.png" /></div>
      <div class="six"><img src="../assets/Qoutient.png" /></div>
      <div class="seven"><img src="../assets/Hourglass.png" /></div>
    </div> -->
    <!--  -->
    <div
      class="some-page-wrapper d-flex justify-content-center align-items-center"
    >
      <div class="row">
        <div class="column">
          <div class="orange-column"><img src="../assets/Layer.png" /></div>
        </div>
        <div class="column">
          <div class="blue-column"><img src="../assets/Sisyphus.png" /></div>
        </div>
        <div class="column">
          <div class="green-column"><img src="../assets/Circooles.png" /></div>
        </div>
      </div>
      <div class="row 2">
        <div class="column">
          <div class="green-column"><img src="../assets/Catalog.png" /></div>
        </div>
        <div class="column">
          <div class="orange-column"><img src="../assets/Qoutient.png" /></div>
        </div>
        <div class="column">
          <div class="blue-column"><img src="../assets/Hourglass.png" /></div>
        </div>
      </div>
    </div>
    <!--  -->
    <!-- <div class="d-flex logo text-center img-fluid flex-row bd-highlight mb-3">
      <div class="p-2 bd-highlight one"><img src="../assets/Layer.png" /></div>
      <div class="p-2 bd-highlight two">
        <img src="../assets/Sisyphus.png" />
      </div>
      <div class="p-2 bd-highlight three">
        <img src="../assets/Circooles.png" />
      </div>
      <div class="p-2 bd-highlight five">
        <img src="../assets/Catalog.png" />
      </div>
      <div class="p-2 bd-highlight six">
        <img src="../assets/Qoutient.png" />
      </div>
      <div class="p-2 bd-highlight seven">
        <img src="../assets/Hourglass.png" />
      </div>
    </div> -->
    <!--  -->
  </section>
</template>
<script>
export default {
  name: 'ButtonVue',
}
</script>
<style scoped>
/* bottom code */
.some-page-wrapper {
  margin: 15px auto;
  text-align: center;
}
.column img {
  height: 48px;
  width: 186.99998474121094px;
  margin: 0 32px;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  /* width: 100%; */
  width: 1440px;
  width: -moz-fit-content;
  width: fit-content;
}

.column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
}

.blue-column {
  /* background-color: blue; */
  /* height: 100px; */
}

.green-column {
  /* background-color: green; */
  /* height: 100px; */
}
@media screen and (min-width: 800px) {
  .column img {
    height: 34px;
    width: 100px;
  }
  .double-column img {
    height: 34px;
    width: 100px;
  }
  .column {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
    flex: 1;
  }

  .double-column {
    flex: 2;
  }
}

/* top code */
section {
  text-align: center;
  height: 100%;
  width: 100%;
  /* padding: 0; */
  margin: 10px auto;
}

/* text */
.container1 h1 {
  height: 72px;
  width: 1024px;

  font-family: 'Inter';
  font-style: normal;
  font-weight: 600;
  font-size: 60px;
  line-height: 72px;
  text-align: center;
  letter-spacing: -0.02em;
  color: #101828;
  margin: 16px auto;
}

/* p */
.container1 .p-tag {
  height: 60px;
  width: 768px;

  /* Text xl/Normal */

  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 30px;

  text-align: center;

  color: #667085;
  margin: 24px auto;
}
/* bottom text */

.b-text p {
  width: 1216px;
  height: 24px;

  /* Text md/Medium */

  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  /* identical to box height, or 150% */

  text-align: center;

  /* Gray/500 */

  color: #667085;

  /* Inside auto layout */

  margin-top: 24px;
  margin-left: auto;
  margin-right: auto;
}
/*  */
/* Image */

.img1 img {
  width: 1216px;
  height: 480px;

  /* Inside auto layout */

  margin: 0 32px;
}

/*  */
/*  */
.container1 {
  display: grid;
  /* height: 100vh; */
  /* width: 100vw; */
  grid-template-columns: 2fr;
  grid-template-rows: 0.2fr;
  grid-template-areas: 'btn btn1';
  grid-gap: 0.2rem;
}

.container1 h1 {
  grid-area: h-1;
}
.container1 p {
  grid-area: p;
}
.container1 .btn0 {
  grid-area: btn;
  /* background: #a7ffeb; */
}
.container1 .btn1 {
  grid-area: btn1;
  /* background: #84ffff; */
}

.img1 img {
  grid-area: img-1;
}

/* .b-text .bottom {
  grid-area: b-text;
} */
/*  */
/* .logo {
} */
/*  */
.logo {
  margin: 0 auto;
  height: 156px;
  width: 1440px;
  display: flex;
  justify-content: center;
  align-content: center;
  text-align: center;
}
.logo img {
  /* margin: auto 20px; */
  margin: auto 24px;
  height: 26.687501907348633px;
  width: 102.10650634765625px;
  border-radius: 0px;
  text-align: center;
}

/* .logo {
  display: grid; */
/* grid-template-columns: 1fr; */
/* grid-template-rows: 1fr;
  grid-template-areas: 'one two three  five six seven';
} */
.logo .one {
  grid-area: one;
}
.logo .two {
  grid-area: two;
}
.logo .three {
  grid-area: three;
}
/* .logo .four {
  grid-area: four;
} */
.logo .five {
  grid-area: five;
}
.logo .six {
  grid-area: six;
}
.logo .seven {
  grid-area: seven;
}
@media only screen and (max-width: 451px) {
  .container1 .btn,
  .img1,
  h1,
  .p-tag {
    /* .b-text  */
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr;

    grid-template-areas:
      'h-1'
      'p'
      'btn'
      'btn1'
      'img-1'
      /* 'b-text' */;
    text-align: center;
  }
  .container1 h1 {
    text-align: center;
    width: 343px;
    height: 88px;
    /* left: 0px;
top: 46px; */
    margin: 16px auto;
    /* Display md/Semibold */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 44px;

    letter-spacing: -0.02em;

    color: #101828;
  }
  .container1 .p-tag {
    width: 343px;
    height: 112px;

    /* Text lg/Normal */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    /* or 156% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    margin: 16px auto;
  }
  .container1 .btn0,
  .btn1 {
    text-align: center;
    /* margin: 0 auto; */
    height: 48px;
    width: 343px;
    margin: 5px auto;
    border-radius: 8px;
  }
  .img1 img {
    height: 199.14266967773438px;
    width: 336.6026611328125px;

    /* left: 34.1307373046875px;
    top: 6.20556640625px; */
    /* padding: 0; */
    border-radius: 0px;
    margin-left: auto;
    margin-right: auto;
  }
  .b-text .bottom {
    width: 343px;
    height: 24px;

    /* Text md/Medium */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    /* identical to box height, or 150% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    /* Inside auto layout */

    margin: 32px auto;
  }

  .b-text .bottom {
    text-align: center;
  }
}

@media only screen and (max-width: 375px) {
  .container1 .btn,
  .img1,
  h1,
  .p-tag {
    /* .bottom { */
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr;

    grid-template-areas:
      'h-1'
      'p'
      'btn'
      'btn1'
      'img-1';
    /* 'b-text'; */
    text-align: center;
  }
  .container1 h1 {
    text-align: center;
    width: 343px;
    height: 88px;
    /* left: 0px;
top: 46px; */
    margin: 16px auto;
    /* Display md/Semibold */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 44px;

    letter-spacing: -0.02em;

    color: #101828;
  }
  .container1 .p-tag {
    width: 343px;
    height: 112px;

    /* Text lg/Normal */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    /* or 156% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    margin: 16px auto;
  }
  .container1 .btn0,
  .btn1 {
    text-align: center;
    /* margin: 0 auto; */
    height: 48px;
    width: 343px;
    margin: 5px auto;
    border-radius: 8px;
  }
  .img1 img {
    height: 199.14266967773438px;
    width: 336.6026611328125px;

    /* left: 34.1307373046875px;
    top: 6.20556640625px; */
    /* padding: 0; */
    border-radius: 0px;
    margin-left: auto;
    margin-right: auto;
  }
  .b-text .bottom {
    width: 343px;
    height: 24px;

    /* Text md/Medium */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    /* identical to box height, or 150% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    /* Inside auto layout */

    margin: 32px auto;
  }
}
/* 375 */

@media only screen and (max-width: 700px) {
  .container1 .btn,
  .img1,
  h1,
  .p-tag {
    /* .bottom { */
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr;

    grid-template-areas:
      'h-1'
      'p'
      'btn'
      'btn1'
      'img-1';
    /* 'b-text'; */
    text-align: center;
  }
  .container1 h1 {
    text-align: center;
    width: 343px;
    height: 88px;
    /* left: 0px;
top: 46px; */
    margin: 16px auto;
    /* Display md/Semibold */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 44px;

    letter-spacing: -0.02em;

    color: #101828;
  }
  .container1 .p-tag {
    width: 343px;
    height: 112px;

    /* Text lg/Normal */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    /* or 156% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    margin: 16px auto;
  }
  .container1 .btn0,
  .btn1 {
    text-align: center;
    /* margin: 0 auto; */
    height: 48px;
    width: 343px;
    margin: 5px auto;
    border-radius: 8px;
  }
  .img1 img {
    height: 199.14266967773438px;
    width: 336.6026611328125px;

    /* left: 34.1307373046875px;
    top: 6.20556640625px; */
    /* padding: 0; */
    border-radius: 0px;
    margin-left: auto;
    margin-right: auto;
  }
  .b-text .bottom {
    width: 343px;
    height: 24px;

    /* Text md/Medium */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    /* identical to box height, or 150% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    /* Inside auto layout */

    margin: 32px auto;
  }
}

/*  */
.container1 .btn0 {
  border: 1px solid #d0d5dd;
}
.container1 .btn1 {
  background: #7f56d9;
  border: 1px solid #7f56d9;
  color: #ffffff;
}

/* image */
/*  */
/*  */
@media only screen and (max-width: 375px) {
  .logo > .one,
  .two,
  .three,
  .five,
  .six,
  .seven {
    display: grid;
    grid-template-columns: 5px 5px;
    grid-template-rows: 5px 5px 5px;

    grid-template-areas:
      'one '
      'two '
      'three five'
      'six  seven';
    text-align: center;
  }

  .logo {
    /* width: 375px;
    height: 254px; */
    height: 134px;
    width: 343px;
    text-align: center;
    display: flex;
    /* flex-direction: column; */
    justify-content: center;
    align-items: center;
    /* flex: 50%; */
  }
  /* .logo .one,
  .three,
  .six {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .logo .two,
  .five,
  .seven {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  } */
  .logo img {
    width: 155.5px;
    height: 34px;
    /* left: 26.5089111328125px;
    top: 0px; */
    border-radius: 0px;
    margin: 0 24px;
  }
}

/* 414px */
@media only screen and (max-width: 414px) {
  .logo > .one,
  .two,
  .three,
  .five,
  .six,
  .seven {
    display: grid;
    grid-template-columns: 5px 5px;
    grid-template-rows: 5px 5px 5px;

    grid-template-areas:
      'one one'
      'two two'
      'three three';
    grid-template-areas:
      ' five five'
      'six'
      'seven';
    text-align: center;
  }

  .logo {
    /* width: 375px;
    height: 254px; */
    /* height: 134px;
    width: 343px; */
    text-align: center;
    display: flex;
    /* flex-direction: column; */
    justify-content: center;
    align-items: center;
    /* flex: 50%; */
  }
  /* .logo .one,
  .three,
  .six {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .logo .two,
  .five,
  .seven {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  } */
  .logo img {
    width: 155.5px;
    height: 34px;
    /* left: 26.5089111328125px;
    top: 0px; */
    border-radius: 0px;
    margin: auto 24px;
  }
}
/* 768 */
@media only screen and (max-width: 768px) {
  .container1 .btn,
  .img1,
  h1,
  .p-tag {
    /* .b-text  */
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr;

    grid-template-areas:
      'h-1'
      'p'
      'btn'
      'btn1'
      'img-1'
      /* 'b-text' */;
    text-align: center;
  }
  .container1 h1 {
    text-align: center;
    width: 343px;
    height: 88px;
    /* left: 0px;
top: 46px; */
    margin: 16px auto;
    /* Display md/Semibold */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 36px;
    line-height: 44px;

    letter-spacing: -0.02em;

    color: #101828;
  }

  .btn0 .btn1 {
    height: 60px;
    width: 121px;

    border-radius: 8px;
    padding: 16px, 28px, 16px, 28px;
  }
  .container1 .p-tag {
    width: 343px;
    height: 112px;

    /* Text lg/Normal */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    /* or 156% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    margin: 16px auto;
  }
  .container1 .btn0,
  .btn1 {
    text-align: center;
    /* margin: 0 auto; */
    height: 48px;
    width: 343px;
    margin: 5px auto;
    border-radius: 8px;
  }
  .img1 img {
    height: 199.14266967773438px;
    width: 336.6026611328125px;

    /* left: 34.1307373046875px;
    top: 6.20556640625px; */
    /* padding: 0; */
    border-radius: 0px;
    margin-left: auto;
    margin-right: auto;
  }
  .b-text .bottom {
    width: 343px;
    height: 24px;

    /* Text md/Medium */

    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    /* identical to box height, or 150% */

    text-align: center;

    /* Gray/500 */

    color: #667085;

    /* Inside auto layout */

    margin: 32px auto;
  }

  .b-text .bottom {
    text-align: center;
  }
}
</style>

<template>
  <section>
    <footer class="container py-5">
      <div class="row">
        <div class="col-6 col-md">
          <h5 class="font-weight-normal">Product</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Overview</a></li>
            <li><a class="text-muted" href="#">Feature</a></li>
            <li><a class="text-muted" href="#">Solutions</a></li>
            <li><a class="text-muted" href="#">Tutorials</a></li>
            <li><a class="text-muted" href="#">Pricing</a></li>
            <li><a class="text-muted" href="#">Releases</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5 class="font-weight-normal">Company</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">About us</a></li>
            <li><a class="text-muted" href="#">Careers</a></li>
            <li><a class="text-muted" href="#">Press</a></li>
            <li><a class="text-muted" href="#">News</a></li>
            <li><a class="text-muted" href="#">Media kit</a></li>
            <li><a class="text-muted" href="#">Contact</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5 class="font-weight-normal">Resources</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Blog</a></li>
            <li><a class="text-muted" href="#">Newsletter</a></li>
            <li><a class="text-muted" href="#">Events</a></li>
            <li><a class="text-muted" href="#">Help centre</a></li>
            <li><a class="text-muted" href="#">Tutorials</a></li>
            <li><a class="text-muted" href="#">Support</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5 class="font-weight-normal">Use cases</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Startups</a></li>
            <li><a class="text-muted" href="#">Enterprise</a></li>
            <li><a class="text-muted" href="#">Government</a></li>
            <li><a class="text-muted" href="#">SaaS</a></li>
            <li><a class="text-muted" href="#">Marketplaces</a></li>
            <li><a class="text-muted" href="#">Ecommerce</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5 class="font-weight-normal">Social</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Twitter</a></li>
            <li><a class="text-muted" href="#">LinkedIn</a></li>
            <li><a class="text-muted" href="#">Facebook</a></li>
            <li><a class="text-muted" href="#">GitHub</a></li>
            <li><a class="text-muted" href="#">AngelList</a></li>
            <li><a class="text-muted" href="#">Dribbble</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5 class="font-weight-normal">Legal</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Terms</a></li>
            <li><a class="text-muted" href="#">Privacy</a></li>
            <li><a class="text-muted" href="#">Cookies</a></li>
            <li><a class="text-muted" href="#">License</a></li>
            <li><a class="text-muted" href="#">Settings</a></li>
            <li><a class="text-muted" href="#">Contact</a></li>
          </ul>
        </div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-12 col-md">
            <small class="d-block mb-3 text-muted bottom-text">
              <p class=""><img src="../assets/Untitle.png" /></p
            ></small>
          </div>
          <div class="col-12 col-md">
            <small class="d-block mb-3 text-muted bottom-text"
              >&copy; 2077 Untitled UI. All rights reserved.</small
            >
          </div>
        </div>
      </div>
    </footer>
  </section>
</template>
<script>
export default {
  name: 'NewFile',
  // data() {
  //   links: ['']
  // },
}
</script>
<style scoped>
body {
  font-family: Rubik, Arial, sans-serif;
  font-weight: 400;
  font-size: 1rem;
  overflow-x: hidden;
  color: #607289;
}

h5 {
  font-size: 1rem;
  line-height: 1.375;
  font-family: Rubik, Arial, sans-serif;
  font-weight: 600;
  color: #030929;
}

a {
  color: #818494;
  font-weight: 500;
  text-decoration: none;
  background-color: transparent;
}

a:hover {
  color: #667085;

  text-decoration: none;
}

footer {
  background: #ffffff;
}
.bottom-text {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  /* identical to box height, or 150% */

  /* Gray/400 */

  color: #98a2b3;

  /* Inside auto layout */

  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 36px 0px;
}
</style>

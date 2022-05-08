<template>
  <section>
    <b-container fluid="sm" class="accordion1 accordion-container">
      <h2>Frequently asked questions</h2>
      <p class="faq">
        Everything you need to know about the product and billing.
      </p>
      <div class="mb-3 accordion">
        <!-- template from bootstrap-vue i modify it -->
        <!-- <b-button v-b-toggle.my-collapse>Toggle Collapse</b-button> -->
        <!-- <b-button v-b-toggle.my-sidebar>Toggle Sidebar</b-button> -->
        <div>
          <h3 v-b-toggle.my-collapse>
            Is there a free trial available
            <b-icon-plus-circle class="plus-icon"></b-icon-plus-circle>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </h3>
        </div>
        <b-collapse id="my-collapse">
          <!-- <b-card title="Collapsible card"
            > -->

          <div title="Collapsible card">
            <p>
              Yes, you can try us for free for 30 days. if you want, we'll
              provide you with a free, personalized <br />
              30-minute onboarding call to get you up and running as soon as
              possible.
            </p>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </div>
          <!-- </b-card> -->
        </b-collapse>
      </div>
      <!--  accordion 2-->
      <div class="mb-3 accordion">
        <div>
          <h3 v-b-toggle.my-collapse2>
            Can I change my plan later?
            <b-icon-plus-circle class="plus-icon"></b-icon-plus-circle>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </h3>
        </div>
        <b-collapse id="my-collapse2">
          <!-- <b-card title="Collapsible card"
            > -->
          <div title="Collapsible card">
            <p></p>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </div>
          <!-- </b-card> -->
        </b-collapse>
      </div>
      <!-- 3 -->

      <div class="mb-3 accordion">
        <div>
          <h3 v-b-toggle.my-collapse3>
            What is your cancellation policy?
            <b-icon-plus-circle class="plus-icon"></b-icon-plus-circle>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </h3>
        </div>
        <b-collapse id="my-collapse3">
          <!-- <b-card title="Collapsible card"
            > -->
          <div title="Collapsible card">
            <p></p>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </div>
          <!-- </b-card> -->
        </b-collapse>
      </div>
      <!-- 4 -->
      <div class="mb-3 accordion">
        <div>
          <h3 v-b-toggle.my-collapse4>
            Can other info be added to an invoice?
            <b-icon-plus-circle class="plus-icon"></b-icon-plus-circle>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </h3>
        </div>
        <b-collapse id="my-collapse4">
          <!-- <b-card title="Collapsible card"
            > -->
          <div title="Collapsible card">
            <p></p>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </div>
          <!-- </b-card> -->
        </b-collapse>
      </div>
      <!-- 5 -->
      <div class="mb-3 accordion">
        <div>
          <h3 v-b-toggle.my-collapse5>
            How does billing work?
            <b-icon-plus-circle class="plus-icon"></b-icon-plus-circle>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </h3>
        </div>
        <b-collapse id="my-collapse5">
          <!-- <b-card title="Collapsible card"
            > -->
          <div title="Collapsible card">
            <p></p>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </div>
          <!-- </b-card> -->
        </b-collapse>
      </div>
      <!-- 6 -->
      <div class="mb-3 accordion">
        <div>
          <h3 v-b-toggle.my-collapse6>
            How do I change my account email
            <b-icon-plus-circle class="plus-icon"></b-icon-plus-circle>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </h3>
        </div>
        <b-collapse id="my-collapse6">
          <!-- <b-card title="Collapsible card"
            > -->
          <div title="Collapsible card">
            <p></p>
            <div class="border-bottom border-dark mx-auto w-50"></div>
          </div>
          <!-- </b-card> -->
        </b-collapse>
      </div>
    </b-container>
    <!-- image -->
    <div
      class="img d-flex justify-content-center align-items-center flex-column"
    >
      <div class="flex-column mt-5">
        <b-img
          class="image"
          src="../assets/Avatargroup.png"
          fluid
          alt="Responsive image"
        ></b-img>
      </div>

      <div class="text">
        <h3>Still have questions?</h3>
        <p>
          Can't find the answer you're lookiing for? Please chat to our friendly
          team.
        </p>
      </div>
      <button>Get in touch</button>
    </div>
  </section>
</template>

<script>
export default {
  name: 'FaqSection',
}
</script>
<style scoped src="../style/FaqSection.css"></style>

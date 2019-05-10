<template>
  <v-container>
    <v-layout column>
      <h1>Contact Us</h1>
      <v-layout class="box-wrapper" row>
        <v-flex class="box" xs12 md4>
          <img src="../assets/logo.png" alt>
          <h1>24/7 Technical Support</h1>
          <p>Mail support will answer any question related to technical issues on server, hosting, and email. Click here for email support request.</p>
          <p>Working Hours: 24 hours x 7 days</p>
          <p>Phone Support: 03-609 7888</p>
          <p>9:00 AM - 5:00 PM (MON - FRI)</p>
        </v-flex>
        <v-flex class="box" xs12 md4>
          <img src="../assets/logo.png" alt>
          <h1>Sales & Inquiries</h1>
          <p>Our sales staff will be happy to answer any questions you have about buying exabytes.my products and services. Click here for sales inquiries.</p>
          <p>Working Hours: 9:00 AM - 5:00 PM GMT +0800</p>
          <p>Phone Support: 03-609 7888</p>
          <p>9:00 AM - 5:00 PM (MON - FRI)</p>
        </v-flex>
        <v-flex class="box" xs12 md4>
          <img src="../assets/logo.png" alt>
          <h1>Billing / Payment</h1>
          <p>Billing Department will be happy to answer any billing questions you have about exabytes.my hosting, products and services. Click here for billing inquiries.</p>
          <p>Working Hours: 9:00 AM - 5:00 PM GMT +0800</p>
          <p>Phone Support: 03-609 7888</p>
          <p>9:00 AM - 5:00 PM (MON - FRI)</p>
        </v-flex>
        <v-card class="v-card">
          <v-card-title primary-title>
            title
          </v-card-title>
          <v-card-actions>
            
          </v-card-actions>
        </v-card>
      </v-layout>
    </v-layout>
  </v-container>
</template>

<script>
export default {
    name: 'ContactDetails'
};
</script>

<style scoped>
.box {
    padding: 5px 10px;
    text-align: center;
    border: 3px solid #f99;
    margin: 10px 15px;
}

.box > img {
    margin: 15px;
}

.v-card {
  font-size: 5rem;
}

@media only screen and (max-width: 768px) {
    .box-wrapper {
        flex-wrap: wrap;
    }
}
</style>

<template>
  <div class="mobile-money-qr-payment"
  data-amount="amount"
  data-api-user-id="'apiUserId'"
  data-external-id="externalId">
  </div>
</template>

<script>
export default {
  name: 'momoqrpayment',
  props: {
    externalId: String,
    amount: Number
  }
}
</script>

<style scoped>
    .mobile-money-qr-payment {
        width: 200px;
        display: inline-block;
    }
</style>

<template>
  <div class="q-pa-md">
    <q-rating
      v-model="ratingModel"
      size="3.5em"
      icon="img:https://cdn.quasar-framework.org/logo/svg/quasar-logo.svg"
    />
  </div>
</template>

<script>
export default {
  data () {
    return {
      ratingModel: 3
    }
  }
}
</script>

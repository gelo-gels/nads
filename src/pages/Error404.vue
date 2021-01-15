<template>
  <div class="fullscreen text-white text-center q-pa-md flex flex-center" style="background: #91abff">
    <div>
      <div class="font-eurostile num__size">
        404
      </div>

      <div class="text-h2 font-europa sub__size" style="opacity:.4">
        Oops. Nothing here...
      </div>

      <q-btn
        class="q-mt-xl font-europa"
        color="white"
        rounded
        text-color="blue"
        unelevated
        to="/"
        label="Go Home"
        no-caps
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'Error404'
}
</script>


<style>
  .num__size {
    font-size: 30vh
  }
  @media (max-width: 480px) {
    .num__size {
      font-size: 25vh
    }
    .sub__size {
      font-size: 34px
    }
  }
</style>
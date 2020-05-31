<template>
  <v-theme-provider dark>
  <base-section>
    <div>
        <button @click="btnLogin"> google </button>
    </div>
  </base-section>
  </v-theme-provider>
</template>

<script>
  export default {
    name: 'SectionLogin',
    methods: {
      btnLogin: function() {
        alert("google")
      }
    }
  }
</script>

<template>
  <div>
    <Nuxt-link to="/">Home</Nuxt-link>
    <b-table striped hover :items="items"></b-table>
    <div>
  <b-button v-b-modal.modal-1>Click me</b-button>

  <b-modal id="modal-1" title="BootstrapVue">
    <p class="my-4">Working with Nuxt.js + Bootstrap Vue </p>
  </b-modal>
</div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          { age: 40, first_name: 'Dickerson', last_name: 'Macdonald' },
          { age: 21, first_name: 'Larsen', last_name: 'Shaw' },
          { age: 89, first_name: 'Geneva', last_name: 'Wilson' },
          { age: 38, first_name: 'Jami', last_name: 'Carney' }
        ]
      }
    }
  }
</script>
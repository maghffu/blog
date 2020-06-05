<template>
  <div>
    <v-btn
      v-for="(item, i) in items.slice(0, large ? items.length : 3)"
      :key="i"
      fab
      class="ma-2"
      color="info"
      :small="!large"
      @click="open(item.link)"
    >
      <v-icon
        dark
        v-text="item.icon"
      />
    </v-btn>
  </div>
</template>

<script>
  export default {
    props: {
      large: {
        type: Boolean,
        default: false,
      },
    },

    data: () => ({
      items: [
        {
          name: 'Twitter',
          icon: 'mdi-twitter',
          link: 'https://twitter.com/maghffu'

        },
        {
          name: 'Facebook',
          icon: 'mdi-facebook',
          link: 'https://facebook.com/maghffu'
        },
        {
          name: 'Email',
          icon: 'mdi-email',
          link: 'maghfurin.dev@gmail.com'
        }
      ],
    }),

    methods: {
      open (link) { 
        window.open(link, '_blank') 
      }
    }
  }
</script>

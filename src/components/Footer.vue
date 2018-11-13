<template>
  <div>
    <footer>
        <p>{{ copyright }}</p>
    </footer>
  </div>
</template>

<script>

export default {
  data() {
    return {
        copyright: 'Built with love by Blessing 😎'
    }
  },
  methods: {

  }
}
</script>

<style scoped>
     footer {
        background: #BF525E;
        padding: 6px;
        /* position:absolute;
        bottom:0;
        width:50%;
        height:30px; */
    }
    p {
        color: white;
        text-align: center;
    }
</style>

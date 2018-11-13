<template>
  <div>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Order</a></li>
            <li><a href="#">Edit</a></li>
        </ul>
    </nav>
  </div>
</template>

<script>

export default {
  components: {
    
  },
  data() {
    return {

    }
  },
  methods: {

  }
}
</script>

<style scoped>
    nav {
        background: #BF525E;
    }

    nav ul {
        list-style-type: none;
        display: flex;
        justify-content: center;
         align-items: center;
        height: 50px;
    }

    nav li {
        display: inline-block;
        font-family: Arial, Helvetica, sans-serif;
        padding: 30px;
    }

    nav a {
        text-decoration: none;
        color: #fff;
    }

    nav a:hover{
        color: #C8A246;
    }

</style>

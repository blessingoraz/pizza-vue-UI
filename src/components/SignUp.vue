<template>
  <div>
    <form>
        <label> Name </label>
        <input type="text" placeholder="Desmond Momo"/>

        <label> Email </label>
        <input type="email" placeholder="Desmond Momo"/>

        <label> Password </label>
        <input type="password" placeholder="Desmond Momo"/>

        <label> Street </label>
        <input type="text" placeholder="Desmond Momo"/>

        <label> Address </label>
        <input type="text" placeholder="Desmond Momo"/>

        <button> Get Started </button>

        <p>Already have an account? Sign In</p>
    </form>
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
    div {
        display: flex;
        justify-content: center;
        margin-top: 70px
    }
    form {
        
    }
    form > input {
        display: block;
        width: 400px;
        margin: 10px 0 10px;
        height: 34px;
        border: 1px solid #ccc;
        border-radius: 3px;
        outline: none;
        padding-left: 10px;
        font-size: 14px;
    }

    label {
        margin-top: 5px;
    }
</style>

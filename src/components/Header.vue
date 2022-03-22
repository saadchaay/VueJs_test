<script>
import Navbar from './Nav.vue';
import Register from './Register.vue';
export default 
{
  components: {
    Navbar,
    Register
  }
}

</script>


<template>
    <header>
        <div class="container">
            <h1>My Blog</h1>
            <Navbar />
            <Register />
        </div>
    </header>
</template> 

<style scoped>
    header {
        background-color: #f1f1f1;
        margin: 0;
        padding: 0;
    }
    header .container{
        padding: 1em 3em;
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: #f1f1f1;
    }
    h1{
        flex: 1;
        font-size: 2em;
        font-weight: bold;
        color: black;
    }
    
</style>
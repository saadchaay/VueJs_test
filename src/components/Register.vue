<script>

export default {
    name: "Register"
}
</script>

<template>
    <ul>
        <li><a href="">Sign Up</a></li>
        <li><a href="">Login</a></li>
    </ul>
</template>

<style scoped>
    ul{
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    li {
        list-style: none;
        border: 5px solid black;
        border-radius: 10px;
        background: black;
        margin: 0 1.2em;
        padding: .2em 1em;
    }
    a {
        text-decoration: none;
        color: white;
    }
    a:hover {
        font-weight: bold;
    }
</style>

<script>
export default 
{
    name: "Navbar"
}
</script>

<template>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="">Article</a></li>
            <li><a href="">Posts</a></li>
            <li><a href="">Profile</a></li>
        </ul>
    </nav>
</template>

<style scoped>
    nav {
        flex: 3;    
    }
    ul {
        display: flex;
        justify-content: center; 
        align-items: center;       
    }
    li {
        list-style: none;
        margin: 0 2em;
    }
    a{
        text-decoration: none;
        color: rgb(41, 41, 41);
        font-size: 1.2em;
    }
    a:hover {
        color: black;
        font-weight: bold;
    }
</style>




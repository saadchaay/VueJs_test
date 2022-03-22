<script >
export default
{
  name: "HomeView",
}
</script>

<template>
    <section>
        <div class="container">
            <div class="content">
                <img src="../assets/banner.png" alt="">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed odit, quas minima doloremque voluptates perferendis. Beatae officiis et accusantium labore perferendis quos voluptas blanditiis veniam, voluptatum amet ipsum numquam maxime.</p>
            </div>
            <div class="right-bar">
                <div class="card-one">
                    <h3>title-card</h3>
                    <img src="../assets/down.jpg" alt="">
                    <p>I'm Shane, a girly girl and lover of life. Join me on the journey to find latest in fashion.</p>
                    <button>Read More</button>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
    section {
        margin: 0;
        padding: 0;
        color: #f1f1f1;
    }
    .container {
        padding: 1em 2em;
        display: flex;
        justify-content: space-between;
    }
    h2, h3, p {
        color: black;
        margin: 0 1.2em;
        text-align: justify;
        margin: 1em 1.2em;
    }
    h3 {
        text-align: center;
        font-weight: bold;
        border-bottom: 1px solid #ff00b3;
    }
    img {
        width: 500px;
        height: 500px;
    }
    .card-one {
        width: 300px;
        height: auto;
        border: 1px solid #f1f1f1;
        display: flex;
        flex-direction: column;
    }
    .card-one img {
        margin-left: auto;
        margin-right: auto;
        width: 100%;
        height: 200px;
        margin: 1em 0;
    }
    button {
        color:#ffafe7;
        font-weight: bold;
        border: none;
        background: none;
        margin: 1.2em 0;
    }
    button:hover {
        cursor: pointer;
        text-decoration: line;
    }
</style>
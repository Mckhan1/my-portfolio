<template>
    <header>
        <div class="wrapper">
            <nav>
                <router-link to="/">Home</router-link>
                <router-link to="/about">About</router-link>
                <router-link to="/skills">My Skills</router-link>
                <router-link to="/contact">Contact me</router-link>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>
header{
    height: 100px;
    width: 100%;
    background: #191D2B;
    display: flex;
}
.wrapper{
    box-shadow: 0px 2px 15px rgb(127, 127, 127);
    height: 100%;
    width: 100%;
    margin: auto;
    /* background: blue; */
    display: flex;
    align-items: center;
    justify-content: center;
}
nav a {
    font-size: 10px;
    margin: 0px 20px;
    color: white;
    font-size: 20px;
    text-decoration: none ;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
</style>
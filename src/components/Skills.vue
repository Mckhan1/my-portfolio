<template>
    <div class="skills">
        <h2>My skills</h2>
        <div class="skills-wrapper">

            <div class="skills-item">
                <p>HTML5</p>
                <div class="item">
                    <p>85%</p>
                    <div class="progress">
                        <span class="html"></span>
                    </div>
                </div>
            </div>
            <div class="skills-item">
                <p>CSS3</p>
                <div class="item">
                    <p>95%</p>
                    <div class="progress">
                        <span class="css"></span>
                    </div>
                </div>
            </div>
            <div class="skills-item">
                <p>JavaScript</p>
                <div class="item">
                    <p>75%</p>
                    <div class="progress">
                        <span class="java"></span>
                    </div>
                </div>
            </div>
            <div class="skills-item">
                <p>Vue 2</p>
                <div class="item">
                    <p>65%</p>
                    <div class="progress">
                        <span class="vue"></span>
                    </div>
                </div>
            </div>
            <div class="skills-item">
                <p>Vue Router</p>
                <div class="item">
                    <p>97%</p>
                    <div class="progress">
                        <span class="router"></span>
                    </div>
                </div>
            </div>
            <div class="skills-item">
                <p>vuex</p>
                <div class="item">
                    <p>70%</p>
                    <div class="progress">
                        <span class="vuex"></span>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'Skills',
}
</script>

<style scoped>
.skills {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    background: #191D2B;
    height: 869px;
    width: 100%;
}

h2 {
    padding: 30px 0;
    color: White;
    font-size: 50px;
    font-weight: 800;
    text-transform: uppercase;

}

.skills-wrapper {
    height: 85%;
    margin: auto;
    width: 50%;
    /* background-color: red; */
    display: flex;
    flex-direction: column;
}

.skills-item {
    display: flex;
    flex-direction: column;
    margin-bottom: 30px;
    justify-content: center;
}

p {
    text-transform: uppercase;
}

.item {
    display: flex;
    align-items: center;
    justify-content: center;
}

p {
    color: gray;
    font-size: 22px;
    margin-bottom: 15px;
}

.progress {
    width: 100%;
    height: 35px;
    border-radius: 25px;
    background-color: gray;
    margin-left: 1rem;
    position: relative;

}

span {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    border-radius: 25px;
    background-color: #27813f;
    transition: all .4s ease-in-out;
    width: 60%;
}

.html {
    width: 85%;
}
.css{
    width: 95%;
}
.java{
    width: 75%;
}
.vue{
    width: 65%;
}
.router{
    width: 97%;
}
.vuex{
    width: 70%;
}

</style>
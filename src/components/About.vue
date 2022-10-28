<template>
    <div class="about">
        <h2>About Me</h2>
        <div class="about-wrapper">
            <div class="left">
                <h2>INFORMATION ABOUT ME</h2>
                <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet labore nihil obcaecati
                    consequatur. Debitis error doloremque, vero eos vel nemo eius voluptatem dicta tenetur modi.
                    <br> <br>
                    La musica delectus dolore fugiat exercitationem a, ipsum quidem quo enim natus accusamus labore
                    dolores nam. Unde. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum non
                    necessitatibus deleniti eum soluta.
                </span>
                <button>Dowland CV</button>
            </div>
            <div class="right">
                <div class="about-item">
                    <span>30+</span>
                    <p>PROJECTS
                        COMPLETED</p>
                </div>
                <div class="about-item">
                    <span>1+</span>
                    <p>YEARS OF EXPERIENCE</p>
                </div>
                <div class="about-item">
                    <span>150+</span>
                    <p>HAPPY
                        CLIENTS</p>
                </div>
                <div class="about-item">
                    <span>400+</span>
                    <p>CUSTOMER
                        REVIEWS</p>
                </div>
            </div>
        </div>
        <h1>My Images</h1>
        <!-- <div class="images">
            <img src="../assets/mc_khan_edited.jpg" alt="">
            <img src="../assets/photo_2022-09-09_22-43-23.jpg" alt="">
            <img src="../assets/photo_2022-09-26_21-38-32.jpg" alt="">
            <img src="../assets/photo_2022-10-23_12-37-58_edited.jpg" alt="">
        </div> -->

    </div>
</template>

<script>
export default {
    name: 'AboutUs'
}
</script>

<style scoped>
.about {
    height: max-content;
    width: 100%;
    background: #191D2B;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

h2 {
    padding: 50px 0 0 0;
    font-size: 50px;
    font-weight: 900;
    color: white;
    text-transform: uppercase;
}

.about-wrapper {
    padding: 70px 0;
    height: max-content;
    width: 90%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: auto;
}

.left {
    height: 80%;
    width: 48%;
    /* background-color: rgb(86, 86, 92); */
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
}

.left h2 {
    font-size: 2rem;
    text-transform: uppercase;
    font-weight: 700;
    color: white;
    margin-bottom: 20px;
}

.left span {
    margin-bottom: 30px;
    color: #dbe1e8;
    width: 75%;
    font-size: 19px;
    line-height: 35px;
}

.left button {
    border-radius: 30px;
    font-weight: 700;
    border: 2px solid #27ae60;
    background: transparent;
    color: white;
    font-size: 20px;
    cursor: pointer;
    width: 220px;
    height: 60px;
}

.right {
    height: 60%;
    width: 48%;
    /* background-color: rgb(207, 146, 146); */
    display: flex;
    align-items: flex-start;
    justify-content: flex-start;
    flex-wrap: wrap;
    /* padding: 20px; */
}

.about-item {
    margin: 30px;
    /* margin-right: 30px; */
    padding: 30px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    height: 200px;
    width: 300px;
    background-color: transparent;
    border-radius: 4px;
    border: 1px solid #2a2e35;
    transition-duration: .5s;
    /* box-shadow: 0px 1px px #27ae60; */
}

.about-item:hover {
    border: 1px solid #27ae60;
    transform: translateY(-5px);
}

span {
    font-size: 3rem;
    font-weight: 700;
    color: #27ae60;
}

p {
    margin-top: 15px;
    padding-left: 3rem;
    position: relative;
    text-transform: uppercase;
    font-size: 1.2rem;
    color: rgb(224, 224, 224);
    letter-spacing: 2px;
}

p::before {
    content: "";
    position: absolute;
    left: 0;
    top: 15px;
    width: 2rem;
    height: 2px;
    background-color: gray;
}

h1 {
    margin: 30px 0;
    font-size: 50px;
    font-weight: 900;
    color: white;
    text-transform: uppercase;
}

.images {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    padding-bottom: 30px;

}

img {
    margin: 20px;
    height: 800px;
    width: 650px;
    border-radius: 15px;
    transition-duration: .5s;
    overflow: hidden;
}

img:hover {
    box-shadow: 0px 5px 15px #b4b4b4;
}
</style>
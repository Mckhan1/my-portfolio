<template>
    <div class="contact">
        <div class="contact-wrapper">
            <h2>CONTACT ME HERE</h2>
            <input type="text" placeholder="YOUR NAME">
            <input type="text" placeholder="YOUR SURNAME">
            <input type="text" placeholder="ENTER SUBJECT">
            <textarea name="" id="" cols="30" rows="10" placeholder="MESSAGE HERE"></textarea>
            <button>Subscibe</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<!-- background: #191D2B; -->
<style scoped>
.contact {
    height: 869px;
    width: 100%;
    background: #191D2B;
}

.contact-wrapper {
    display: flex;
    height: 100%;
    width: 80%;
    margin: auto;
    flex-direction: column;
    /* background-color: blue; */
    align-items: center;
    justify-content: center;
}
h2{
    margin-bottom: 50px;
    font-size: 40px;
    text-transform: uppercase;
    color: white;
}
input{
    border-radius: 30px;
    font-weight: inherit;
    font-size: inherit;
    font-family: inherit;
    height: 50px;
    width: 600px;
    padding: 20px 30px;
    outline: none;
    border: none;
    background-color: #2a2e35;
    color: white;
    margin-bottom: 20px;
}

textarea{
    border-radius: 30px;
    font-weight: inherit;
    font-size: inherit;
    font-family: inherit;
    padding: 20px 40px;
    outline: none;
    border: none;
    background-color: #2a2e35;
    width: 600px;
    color: white;
    resize: none;
}

button{
    border-radius: 30px;
    font-weight: 700;
    border: 2px solid #27ae60;
    background: transparent;
    color: white;
    font-size: 20px;
    cursor: pointer;
    width: 220px;
    height: 60px;
    margin-top: 30px;
}

</style>
<template>
    <div class="content_skills">
        <h1>МОИ НАВЫКИ</h1>
        <nav>
            <ul>
                <li class="ok">
                    <img src="./../assets/vue.svg" class="img">
                    <p>VUE</p>
                </li>
                <li class="ok">
                    <img src="./../assets/html.svg" class="img">
                    <p>HTML</p>
                </li>
                <li class="ok">
                    <img src="./../assets/css.svg" class="img">
                    <p>CSS</p>
                </li>
                <li class="ok">
                    <img src="./../assets/javascript.svg" class="img">
                    <p>JAVASCRIPT</p>
                </li>
                <li class="ok">
                    <img src="./../assets/mongodb.svg" class="img">
                    <p>MONGODB</p>
                </li>
                <li class="ok">
                    <img src="./../assets/bootstrap.svg" class="img">
                    <p>BOOTSTRAP</p>
                </li>
                <li class="ok">
                    <img src="./../assets/nodejs.svg" class="img">
                    <p>NODE.JS</p>
                </li>
            </ul>
        </nav>
    </div>
</template>
<style scoped>
.content_skills {
    justify-content: center;
    background-color: #2d3142;
    color: white;
}
nav ul {
    display: flex;
    gap: 90px;
    justify-content: center;
    text-align: center;
    text-transform: uppercase;
    font-size: 40px;
}
.content_skills {
    padding: 60px 0;
    text-align: center;
}
.content_skills h1 {
    font-size: 50px;
    padding-bottom: 50px;
}
.img {
    width: 40px;
    height: 40px;
}
.img:hover {
    width: 80px;
    height: 80px;
    transition: all 1s;
}
</style>
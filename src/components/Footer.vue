
<template>
    <footer class="footer" id="footer">
        <div class="left_block">
            <h1>Зайцев Константин</h1>
            <p>(с) 2024. Все права защищены</p>
        </div>
        <div class="right_block">
            <a href="https://t.me/+QTKuypFG3LNiYTZi" target="_blank"><img src="./../assets/telegram.svg" class="img"></a>
            <a href="https://t.me/+QTKuypFG3LNiYTZi" target="_blank"><img src="./../assets/vk.svg" class="img"></a>
            <a href="https://t.me/+QTKuypFG3LNiYTZi" target="_blank"><img src="./../assets/whatsapp.svg" class="img"></a>
        </div>
    </footer>
</template>
<style scoped>
.footer {
    display: flex;
    justify-content: space-between;
    padding: 100px 402px;
}
.right_block ul {
    display: flex;
    gap: 30px;
}
.img:hover {
    width: 80px;
    height: 80px;
}
</style>
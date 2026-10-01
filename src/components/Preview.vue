<script setup>
</script>

<template lang="">
    <div>
        <div class="title">
            <h1>Эксклюзивная <br> и нестандартная <br> мебель для дома</h1>
            <a href="#">Заказать проект</a>
        </div>
        <div class="content">
            <div class="left-block">
                <p>Мы можем произвести любую мебель для <br>вашего проекта и найти производственное <br> решение любой задумки.</p>
                <img src="./assets/preview_1.png">
            </div>
            <div>
                <img src="./assets/preview_2.png">
            </div>
        </div>
    </div>
</template>
<style scoped>

.left-block{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.title h1{
    font-size: 72px;
    line-height: 120%;
    text-transform: uppercase;
}

.title{
    display: flex;justify-content: space-between;
    align-items: end;
}

.title a{
    font-size: 18px;
    text-decoration: underline;
    text-transform: uppercase;
    color: var(--text-main);
}

.content{
    display: flex;
    justify-content: space-between;
}

</style>

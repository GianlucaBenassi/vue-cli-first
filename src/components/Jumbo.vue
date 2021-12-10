<template>

    <div class="jumbo">
        <h2>Questo è il Jumbotron!</h2>
    </div>

</template>

<script>

export default {
    name: 'Jumbo'
}

</script>

<style scoped>

.jumbo {
    height: 500px;
    background-image: url('../assets/jumbo.png');
    background-size: cover;
    background-position: bottom;
    display: flex;
    justify-content: center;
    align-items: center;
}

h2 {
    font-size: 40px;
}

</style>
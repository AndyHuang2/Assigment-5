<script setup>
</script>
<template>
    <div class = header>
        <h1>NotNetflix</h1>
    </div>
    <div class="buttons">
        <RouterLink to="/register" class="button">Register</RouterLink>
        <RouterLink to="/login" class="button">Login</RouterLink>
    </div>
</template>
<style scoped>
h1 {
    color: white;
    text-align: center;
    font-size: 50px;
}

.header {
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: 400;
    font-style: italic;
    background-color: black;
    text-align: center;
    width: 100%;
    padding: 20px 0;
}

.buttons {
    display: flex;
    justify-content: center;
    background-color: black;
    padding: 20px 0;
}

.button {
    padding: 10px 20px;
    margin: 0 10px;
    background-color: #333;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-size: 16px;
    transition: background-color 0.3s ease;
}

.button:hover {
    background-color: #555;
}
</style>
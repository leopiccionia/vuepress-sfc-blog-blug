<template>
    <div class="wrapper">
        <header>Layout header</header>
        <main><slot/></main>
        <footer>Layout footer</footer>
    </div>
</template>

<style scoped>
    header, footer {
        background-color: pink;
        padding: 20px;
        width: 100%;
    }
</style>

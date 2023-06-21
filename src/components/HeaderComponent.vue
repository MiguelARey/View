<template>
    <header class="mainHeader">
        <img src="../assets/img/logo-white.svg" />
    </header>
</template>

<script>
export default {
    name: "HeaderComponent",
};
</script>

<style scope>
.mainHeader {
    background-color: #07cc59;
    height: 10vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 1%;
}
.mainHeader > img {
    width: 10%;
}
</style>

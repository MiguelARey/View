<template>
    <nav class="mainNav">
        <section class="mainSearch">
            <input type="text" placeholder="Search the product!"/>
            <input type="submit" value="&#xf002;"/>
        </section>
        <article>
            <p>Login</p>
            <p>Sign Up</p>
            <!-- <router-link to="/login">Login</router-link>
            <router-link to="/signUp">Sign Up</router-link> -->
        </article>
    </nav>
</template>

<script>
export default {
    name: "HeaderComponent",
};
</script>

<style scope>
.mainNav {
    height: 3vh;
    border-bottom: 1px solid #D9D9D9;
    padding: 0.5% 2%;
    display: flex;
    justify-content: space-between;
}
.mainNav > section {
    display: flex;
    column-gap: 1vw;
    align-items: center;
}
.mainNav > article {
    display: flex;
    column-gap: 2vw;
    align-items: center;
}
.mainNav > .mainSearch > img {
    width: 20px;
}
.mainNav > .mainSearch > input:first-child {
    border: 1px solid #07cc59;
    border-radius: 10px;
    padding: 2% 4%;
    width: 20vw;
}
.mainNav > .mainSearch [type="submit"] {
    font-family: "Font Awesome\ 5 Free";
    font-size: 20px;
    font-weight: 900;
    content: "\f002";
    border: none;
    background-color: transparent;
    color: #07cc59;
}
.mainNav > .mainSearch [type="submit"]:hover {
    cursor: pointer;
}
.mainNav > article > p:hover {
    cursor: pointer;
    color: #07cc59;
}
</style>

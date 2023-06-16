<template>
    <section class="signIn">
        <img src="../../assets/img/logo-green.svg" alt="logo" />
        <article class="signInFormContainer">
            <form method="post">
                <input type="email" name="email" placeholder="Email" />
                <input type="password" name="password" placeholder="Password" />
                <button type="submit">Sign In</button>
            </form>
            <article>
                <a href="#">Sign Up</a>
            </article>
            <a href="#">Visit the site without signing in</a>
        </article>
    </section>
</template>

<script>
export default {
    name: "LoginPageComponent",
};
</script>

<style scope>
.signIn {
        height: 100vh;
        background-color: #212121;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        row-gap: 4vh;
    }
    .signIn img {
        width: 15%;
    }
    .signInFormContainer {
        width: 40%;
        display: flex;
        flex-direction: column;
        row-gap: 3vh;
    }
    .signInFormContainer > form {
        height: 250px;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        background-color: white;
        padding: 4%;
        border-radius: 10px;
        border: 1px solid #d9d9d9;
    }
    .signInFormContainer > form > input::placeholder {
        color: gray;
        font-size: 15px;
    }
    .signInFormContainer > form > input {
        border: none;
        border-bottom: 1px solid #d9d9d9;
        padding: 2%;
    }
    .signInFormContainer [type="submit"] {
        background-color: #07cc59;
        color: white;
        border: none;
        padding: 3%;
        border-radius: 7px;
    }
    .signInFormContainer [type="submit"]:hover,
    .signInFormContainer > article > a:hover {
        background-color: #212121;
        color: white;
        transition: .4s;
    }
    .signInFormContainer > article {
        display: flex;
        justify-content: center;
    }
    .signInFormContainer > article > a {
        text-decoration: none;
        width: 40%;
        background-color: #07cc59;
        color: white;
        padding: 2%;
        border-radius: 7px;
        text-align: center;
    }
    .signInFormContainer > a {
        background-color: transparent;
        text-decoration: underline;
        color: white;
        text-align: center;
    }
    .signInFormContainer > a:hover {
        font-weight: 700;
    }
    .signInFormContainer p {
        color: red;
        font-size: 13px;
        padding: 0% 2% 3%;
    }
</style>

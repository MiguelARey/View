<template>
    <section class="signUp">
        <img src="../../assets/img/logo-green.svg" alt="Logo" />
        <article class="signUpFormContainer">
            <form method="post">
                <section class="signUpSection">
                    <article class="signUpInput">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required />
                    </article>
                    <article class="signUpInput">
                        <label for="password">Password</label>
                        <input
                            type="password"
                            id="password"
                            name="password"
                            required
                        />
                    </article>
                    <article class="signUpInput">
                        <label for="confirmPw">Confirm Password</label>
                        <input
                            type="password"
                            id="confirmPw"
                            name="confirmPw"
                            required
                        />
                    </article>
                    <article class="signUpInput">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required />
                    </article>
                    <article class="signUpInput">
                        <label for="phoneNumber">Phone Number</label>
                        <input
                            type="tel"
                            id="phoneNumber"
                            name="phoneNumber"
                            required
                        />
                    </article>
                    <article class="signUpInput">
                        <label for="address">Address</label>
                        <input type="text" id="address" name="address" required />
                    </article>
                </section>
                <button type="submit">Sign Up</button>
            </form>
        </article>
    </section>
</template>

<script>
export default {
    name: "SignUpPageComponent",
};
</script>

<style scope>
    .signUp {
        height: 100vh;
        background-color: #212121;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        row-gap: 4vh;
    }
    .signUp img {
        width: 15%;
    }
    .signUpFormContainer {
        width: 35%;
        display: flex;
        flex-direction: column;
        row-gap: 2vh;
    }
    .signUpFormContainer > form {
        display: flex;
        flex-direction: column;
        row-gap: 4vh;
        background-color: white;
        padding: 4%;
        border-radius: 10px;
        border: 1px solid #d9d9d9;
    }
    .signUpSection {
        display: flex;
        flex-direction: column;
        row-gap: 2vh;
    }
    .signUpFormContainer > form label {
        color: gray;
        font-size: 15px;
        text-align: left;
    }
    .signUpFormContainer [type="submit"] {
        background-color: #07cc59;
        color: white;
        border: none;
        padding: 2%;
        border-radius: 7px;
    }
    .signUpFormContainer [type="submit"]:hover {
        background-color: #212121;
        color: white;
        transition: .4s;
    }
    .signUpFormContainer article {
        display: flex;
        flex-direction: column;
        row-gap: 0.5vh;
    }
    .signUpInput > input {
    padding: 1%;
    border-radius: 5px;
    border: 1px solid #d9d9d9;
    }
</style>
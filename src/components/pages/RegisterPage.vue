<template>
    <div class="login wrapper">
        <div class="login-form register-form">
            <h2>Register</h2>
            <form action="">
                <div class="input-wrapper">
                    <label for="email">First name:</label>
                    <input type="email" name="email">
                </div>
                <div class="input-wrapper">
                    <label for="email">Last name:</label>
                    <input type="email" name="email">
                </div>
                <div class="input-wrapper">
                    <label for="email">Email:</label>
                    <input type="email" name="email">
                </div>
                <div class="input-wrapper">
                    <label for="password">Password:</label>
                    <input type="password" name="password">
                </div>
                <div class="input-wrapper">
                    <label for="password">Password confirm:</label>
                    <input type="password" name="password">
                </div>
                <button class="btn">Login</button>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: 'LoginPage'
}
</script>

<style>
.register-form {
    height: 80%;
}
</style>
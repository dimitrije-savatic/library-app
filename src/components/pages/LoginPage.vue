<template>
    <div class="login wrapper">
        <div class="login-form">
            <h2>Login</h2>
            <form action="">
                <div class="input-wrapper">
                    <label for="email">Email:</label>
                    <input type="email" name="email">
                </div>
                <div class="input-wrapper">
                    <label for="password">Password:</label>
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
.login {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.1rem;
}

.login-form {
    width: 35%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: #293241;
    border-radius: 8px;
    box-shadow: 0px 0px 33px 2px rgba(61,90,128,1);
    padding-top: 1rem;
    padding-bottom: 1rem;
}

form {
    width: 60%;
    margin-top: 1rem;
}

.input-wrapper {
    display: flex;
    flex-direction: column;
    margin-bottom: 2rem;
}

input {
    margin-top: 0.5rem;
    height: 2rem;
    font-size: 1.1rem;
    border-radius: 8px;
    border: none;
    outline: none;
    color: #3d5a80;
    padding-left: 0.5rem;
}

.btn {
    width: 30%;
    height: 2rem;
    font-size: 1rem;
    font-weight: bold;
    margin-bottom: 1rem;
    border-radius: 8px;
    border: none;
    background-color: #e0fbfc;
    color: #3d5a80;
    cursor: pointer;
}
</style>
<template>
    <header>
        <nav>
            <router-link class="router-link" to="/" active-class="active">Home</router-link>
            <router-link class="router-link" to="/login" active-class="active">Login</router-link>
            <router-link class="router-link" to="/register" active-class="active">Register</router-link>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'HeaderComp'
}
</script>

<style>
header{
    height: 6vh;
    width: 100%;
    background-color: #3d5a80 ;
    display: flex;
    align-items: center;
    justify-content: center;
}
nav{
    width: 10%;
    display: flex;
    justify-content: space-evenly;
}
.router-link{
    text-decoration: none;
    color: #e0fbfc;
    font-size: 1rem;
}
</style>
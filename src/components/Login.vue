<template>
    <div>
        <h3>Username</h3>
        <input v-model="username" type="text">
        <h3>Password</h3>
        <input v-model="password" type="text">
        <button @click="login">Login</button>

    </div>
</template>

<script>
    export default {
        name:"login-page",
        data() {
            return {
                username:"",
                password:""
            };
        },
        
        
    }
</script>

<style scoped>

</style>
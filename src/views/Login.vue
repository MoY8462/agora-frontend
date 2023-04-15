<script setup>
import Input from '../components/base/Input.vue'
import Button from '../components/base/Button.vue'
</script>

<template>
    <div class="login">
        <div class="login__container">
            <section >
                <svg class="icon icon_agora_icon"></svg>
                <h1>Welcome to Agora</h1>
            </section>
            <section>
                <Input :type="'email'" :title="'Email'" :placeholder="'example@dominio.com'"/>
                <Input :type="'password'" :title="'Password'" :placeholder="'*********'"/>
                <Button class="bg-blue-100 hover:bg-blue-200">Login</Button>
            </section>
            <section></section>
        </div>
    </div>
</template>
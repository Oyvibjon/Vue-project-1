<template>
    <!-- 3. Use -->
    <LoginComponent></LoginComponent>
</template>

<script>
//1. Import
import LoginComponent from './LoginComponent.vue';

//2. Bind
export default {
    name: 'MyRootComponent',
    components: {
        LoginComponent,
    }
}
</script>

<template>
    <header>
        <h1>{{ title }}</h1>
        <Button />
    </header>
</template>

<script>

    import Button from './components/Button.vue';

    export default {
        name: 'header',
        props: {
            title: String,
        },
        components: {
            Button
        }
    }
</script>

<style scoped>
    header {
      display: flex;  
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }
</style>
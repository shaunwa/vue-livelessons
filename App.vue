<template>
    <h1>Welcome to {{ siteName }}!</h1>
</template>

<script>
export default {
    name: 'MyComponent',
    data() {
        return {
            siteName: 'Learn Vue LiveLessons',
        };
    }
}
</script>

<style>
h1 {
    color: red;
}
</style>
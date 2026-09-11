<template>
    <div>
        <h1>Footer {{ company}}</h1>
    </div>
</template>

<script>
    export default {
        name: 'AppFooter',
        props: {
            company: String
        }
    }
</script>
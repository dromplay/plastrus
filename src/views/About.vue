<template>
    <div id="app">
        {{ message }}
    </div>
</template>

<script>
    import Vue from 'vue'

    var app = new Vue({
        el: '#app',
        data: {
            message: 'Привет, Vue!'
        }
    })
</script>
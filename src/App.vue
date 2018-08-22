<template>
    <div>{{data}}</div>
</template>

<script lang="ts">
    import {Component, Vue} from 'vue-property-decorator'
    import data from './data.json'

    @Component({})
    export default class App extends Vue {
        data = data
    }
</script>

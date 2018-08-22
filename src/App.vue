<template>
    <div>{{ names }}</div>
</template>

<script lang="ts">
    import {Component, Vue} from 'vue-property-decorator'
    import names from './data.json'

    @Component({})
    export default class App extends Vue {
        names = names.filter(item => item.namex.includes('s'))
    }
</script>

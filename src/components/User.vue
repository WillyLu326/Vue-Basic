<template>
    <div>
        <h1>User Information</h1>
        <div class="row">
            <app-servers></app-servers>
        </div>
    </div>
</template>

<script>
    import Servers from './Servers.vue';
    export default {
        components: {
            'app-servers': Servers
        }
    }
</script>

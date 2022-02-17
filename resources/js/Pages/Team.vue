<template>
    <Layout>
        <div>This is the team page</div>
    </Layout>
</template>

<script>
import Layout from "../components/Layout";
import { Head } from '@inertiajs/inertia-vue3'
export default {
    name: "Team",
    components: {Layout, Head},
    props: {
        people: {
            type: Array,
            required: true
        }
    }
}
</script>

<style scoped>

</style>

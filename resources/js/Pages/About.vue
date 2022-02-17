<template>
    <Layout>
        <div>This is the about page</div>
        <div>{{ description }}</div>
    </Layout>
</template>

<script>
import Layout from "../components/Layout";
import { Head } from '@inertiajs/inertia-vue3'

export default {
    name: "About",
    components: {Layout, Head},
    props: {
        description: {
            type: String,
            required: true
        }
    }
}
</script>

<style scoped>

</style>

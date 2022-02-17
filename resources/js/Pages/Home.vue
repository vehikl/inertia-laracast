<template>
    <Layout>
        <div>This is the vue home component {{ company }}</div>
    </Layout>
</template>

<script>
import Layout from "../components/Layout";
import { Head } from '@inertiajs/inertia-vue3'

export default {
    name: "Home",
    components: {Layout, Head},
    props: {
        company: {
            type: String,
            required: true
        }
    }
}
</script>

<style scoped>

</style>

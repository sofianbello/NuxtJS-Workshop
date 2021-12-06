<template>
    <div> {{ work.name}} </div>
</template>

<script>
import { ART_WORKS } from "@/content/works.js";

export default {
    data() {
        return {
            works: ART_WORKS.find(system => system.slug === this.$route.params.name),
        }
    },
}
</script>

<style scoped>
</style>

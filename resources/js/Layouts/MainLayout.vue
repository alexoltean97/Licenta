<template>
    <Link href="/">Main Page</Link>
    <Link href="/hello">Show Page</Link>
    <slot></slot>
</template>

<script>
import {Link} from "@inertiajs/vue3";

export default {
    name: "MainLayout",
    components:{
        Link
    }
}
</script>

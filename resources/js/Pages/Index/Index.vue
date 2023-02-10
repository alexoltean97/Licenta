<template>
 <MainLayout>
     <div>Indexplm</div>

     <div>
         The message is {{message}}
     </div>
 </MainLayout>
</template>

<script>
import {Link} from "@inertiajs/vue3";
import MainLayout from "../../Layouts/MainLayout.vue";


export default {
    name: "Index",

    components:{
        MainLayout,
        Link
    },

    props:{
        message: String
    }

}
</script>

<style scoped>

</style>

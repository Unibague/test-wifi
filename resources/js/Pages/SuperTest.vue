<template>
    <AuthenticatedLayout>


    <h2> Ok let's go</h2>


    <!--Authenticated-->

    </AuthenticatedLayout>
</template>

<script>
import AuthenticatedLayout from "@/Layouts/AuthenticatedLayout";
import {InertiaLink} from "@inertiajs/inertia-vue";
import ConfirmDialog from "@/Components/ConfirmDialog";

export default {
    components: {
        AuthenticatedLayout,
        InertiaLink,
        ConfirmDialog
    },
    data: () => ({
        showDialog: false
    }),
    methods: {




    }
}
</script>

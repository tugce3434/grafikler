<template>
    <div class="card">
        <div class="card-body">
            <p>{{ dil }}</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Veriler",
        props:{
            dil :{
                type: String,
                require: true
            }
        }
    }
</script>

<style scoped>

</style>
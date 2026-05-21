<template>

    <footer class="footer
                animate__animated
            animate__fadeInDown
            animate__delay-4s
            p-5
    ">
        <p>Pie de página</p>
    </footer>
</template>



<script setup>

</script>




<style lang="scss" scoped>

@use "@/assets/sass/abstracts/variables" as *;

.footer {
    background-color: $color-cuarto;
    color: #fff;
    padding: 10px;
    border-bottom: 10px solid $color-terciario;
}

</style>
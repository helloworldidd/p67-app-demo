<template>
    <nav class="navbar">
        <ul>
            <li>
                <a class="btn btn-primary" href="#">
                    <i class="bi bi-house"></i>
                    Home
                </a>
            </li>
            <li>
                <a class="btn btn-primary" href="#">
                    <i class="bi bi-person-fill"></i>
                    About
                </a>
            </li>
            <li>
                <a class="btn btn-primary" href="#">
                    <i class="bi bi-chat-fill"></i>
                    Contact
                </a>
            </li>
        </ul>
    </nav>
</template>

<script setup>

</script>

<style lang="scss" scoped>
@use "@/assets/sass/abstracts/variables" as *;
@use "@/assets/sass/abstracts/mixins" as *;

.navbar{
    background-color: $color-terciario; //rgb(51, 73, 81);
    color: #fff;
    padding: 10px;

    ul{
        @include flex-center;
        width: fit-content;
        gap: 10px;
        list-style: none;
        margin: 0;
        padding: 0;
    }

}


</style>
<template>
    <nuxt-link
        class="primaryButton active"
        :to="'/'"
    >   
        {{title}}
    </nuxt-link>
</template>

<style lang="scss" scoped>
    .primaryButton{
        background-color: #6D2080;
        color: #FFFFFF;
        border-radius: 10px;

        padding: 10px 36px;

        font-size: 14px;
        text-decoration: none;
    }
</style>

<script>
export default {
    props: {
        title: String
    }
}
</script>
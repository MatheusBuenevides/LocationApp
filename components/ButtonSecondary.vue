<template>
    <nuxt-link
        class="secondaryButton active"
        :to="'/'"
    >   
        <v-icon :color="'#6D2080'">mdi-keyboard-return</v-icon>
        
        {{title}}
    </nuxt-link>
</template>

<style lang="scss" scoped>
    .secondaryButton{
        background-color: #FFFFFF;
        color: #6D2080;
        border: solid 1px #6D2080;

        padding: 2px 16px;

        font-size: 18px;
        font-weight: 400;
        text-decoration: none;


        display: flex;
        justify-content: space-between;
        gap: 20px;
    }
</style>

<script>
export default {
    props: {
        title: String
    }
}
</script>
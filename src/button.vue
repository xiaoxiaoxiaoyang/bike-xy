<template>
    <button class="g-button">按钮</button>
</template>

<script>
    export default {
    }
</script>

<style scoped lang="scss">
    .g-button{
        height: var(--button-height);
        font-size: var(--font-size);
        padding: 0 1em;
        border-radius:var(--border-radius);
        border: 1px solid var(--border-color);
        &:hover{
            border-color: var(--border-color-hover);
        }
        &:active{
            background-color: var(--button-active-bg) ;
        }
        &:focus{
            outline: none;
        }    background: var(--button-bg);
    }

</style>

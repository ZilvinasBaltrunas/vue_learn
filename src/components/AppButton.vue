<template>
    <div>
        <button class="button"><slot></slot></button>
    </div>
</template>

<script>
export default {
    name: "AppButton"
}
</script>

<style lang="scss" scoped>
    .button {
        border-radius: 5px;
    }
</style>
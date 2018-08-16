<template>
    <div class="field">
        <div class="control">
            <input class="input" :value="value" :placeholder="placeholder" type="text" 
                @input="$emit('input',$event.target.value)">
        </div>
    </div>
</template>

<script>
export default {
    name: 'AppInput',
    props: ['value', 'placeholder'],
}
</script>

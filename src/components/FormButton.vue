<template>
    <button :class="['m-button', type ? `m-button--${type}` : false, size ? `m-button--${size}` : false]">
        {{text}}
    </button>
</template>

<script>
export default {
    name: "FormButton",
    props: {
        text: String,
        type :{ type : String, default: "primary"},
        size: { type: String, default: "primary"},
    },
    computed: {
        
    }
}
</script>
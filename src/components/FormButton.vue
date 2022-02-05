<template>
    <button :class="['m-button', look ? `m-button--${look}` : false, size ? `m-button--${size}` : false]" :type='type' :disabled="disabled">
        {{text}}
    </button>
</template>

<script>
export default {
    name: "FormButton",
    props: {
        text: String,
        type :{ type : String, default: "button"},
        look :{ type : String, default: "primary"},
        size: { type: String, default: "medium"},
        disabled: { type: String, default: 'disabled'}
    },
    computed: {
        
    }
}
</script>
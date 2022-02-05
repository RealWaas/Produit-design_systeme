<template>
    <component :is="tag" :class="['text', `text-color--${color}`]">
        {{text}}
    </component>
</template>

<script>
export default {
    name: "FormText",
    props: {
        text: String,
        tag: { type : String, default: "h1"},
        color: { type: String, default: "black"},
        //type: { type: String },
        //class: { type: String}
    },
    computed: {
        
    }
}
</script>
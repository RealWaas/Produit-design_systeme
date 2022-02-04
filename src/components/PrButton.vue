<template>
    <button :type="type" :style="style">
        {{text}}
    </button>
</template>

<script>
export default {
    name: "PrButton",
    props: {
        text: String,
        type: {type: String, required:false},
        color :{ type : String, default: "primary"},
        backgroundColor: { type: String, default: "primary"},
    },
    computed: {
        style() {
            return 'background-color: ' + this.backgroundColor + '; color: ' + this.color;
        }
    }
}
</script>
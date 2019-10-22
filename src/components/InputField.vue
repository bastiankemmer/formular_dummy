<template>
    <div class="form-group">
        <label :for="id">{{label}}</label>
        <input :id="id" class="form-control" :placeholder="placeholder" :type="type" :value="value" :disabled="disabled"/>
    </div>
</template>

<script>
    export default {
        name: "InputField",
        props: {
            "label": String,
            "placeholder": String,
            "type": {
                type: String,
                default: "text"
            },
            "value": {
                type: String,
                required: false
            },
            "disabled": {
                type: Boolean,
                default: false
            }
        },
        data () {
            return {
                id: null
            }
        },
        mounted () {
            this.id = this._uid
        }
    }
</script>

<style scoped>

</style>
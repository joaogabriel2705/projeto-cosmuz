<script>
    export default {
        props: {
            buttonText: {
                type: String,
                required: true,
            },
            showIcon: {
                type: Boolean,
                default: false,
            }
        }
    }
</script>

<template>
  <button>
    {{ buttonText }}
  </button>
</template>


<style lang="scss" scoped>
    @import 'Button.scss';
</style>
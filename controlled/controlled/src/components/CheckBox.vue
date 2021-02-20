<template>
    <div>
        <input type="checkbox" :value="value" @click="toggleCheckBox">
    </div>
</template>

<script>
    export default{
        //:value 프롭스에 고정값 value
        props: ['value'], //부모에서 내려올떄는 false
        methods:{
            toggleCheckBox(){
                //올릴때는 true로 변경해서 부로로올리기
                this.$emit('input', !this.value)
            }
        }
    }
</script>

<style scoped>

</style>
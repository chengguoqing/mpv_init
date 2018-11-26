<template>
<div >
    <van-button type="primary">主要按钮</van-button>
    <van-cell-group>
        <van-cell title="单元格" value="内容" />
        <van-cell title="单元格" is-link />
    </van-cell-group>
    <van-cell-group>
        <van-field
            v-model="username"
            clearable
            label="用户名"
            placeholder="请输入用户名"
        />
    <van-field
            v-model="username"
            clearable
            label="用户名"
            icon="arrow"
            placeholder="请输入用户名"
        /> 
            </van-cell-group>
    

  
</div>
</template>
<script>
    import Toast from '@/../static/vant/toast/toast'
    export default {
        data() {
            return {
               
            }
        },
        components: {

        },
        methods: {
            close_e() {
                Toast.fail('失败文案');

            }
        },
        mounted() {

        },
    }

</script>
<style scoped>


</style>

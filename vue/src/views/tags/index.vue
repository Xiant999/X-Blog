<template>
    <div class="app-container">
        <!-- 添加框 -->
        <el-card>
            <el-row :gutter="8">
                <el-col :xs="{span: 24}" :sm="{span: 24}" :md="{span: 24}" :lg="{span: 12}" :xl="{span: 12}"
                        style="padding-right:8px;margin-bottom:30px;">
                    <Tags/>
                </el-col>
                <el-col :xs="{span: 24}" :sm="{span: 24}" :md="{span: 24}" :lg="{span: 12}" :xl="{span: 12}"
                        style="margin-bottom:30px;">
                    <Category/>
                </el-col>
            </el-row>
        </el-card>
    </div>
</template>

<script>
    import Tags from './components/Tags'
    import Category from './components/Category'

    export default {
        name: "index",
        components: {Tags, Category}
    }
</script>

<style scoped>
    .tags-container {
        /*padding: 32px;*/
    }
</style>

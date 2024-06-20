<template>
    <div>
        <el-button type="primary" size="default">主要按钮</el-button>
        <el-button type="success">Success</el-button>
        <el-button type="info">Info</el-button>
        <el-button type="warning">Warning</el-button>
        <el-button type="danger">Danger</el-button>
        <div class="example-pagination-block">
            <div class="example-demonstration">When you have few pages</div>
                <el-pagination layout="prev, pager, next" :total="50" />
  </div>
    </div>
</template>

<script setup lang="ts">

</script>
    import {Elbutton} from 'element-plus'
    export default {
        components: { ElButton},
    }
<style scoped>
/* .example-pagination-block + .example-pagination-block {
  margin-top: 50px;
} */
</style>
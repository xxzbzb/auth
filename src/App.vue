<template>
    <el-container :gutter="24">
        <el-header>Header</el-header>
        <el-main >
					<mainContainer></mainContainer>
				</el-main>
        <el-footer>Footer</el-footer>
    </el-container>
</template>

<script>
import mainContainer from '@/components/MainContainer'
export default {
  name: 'app',
	components: {
		mainContainer
	}
}
</script>

<style>
    html,body,#app,.el-container{
        /*设置内部填充为0，几个布局元素之间没有间距*/
        padding: 0px;
        /*外部间距也是如此设置*/
        margin: 0px;
        /*统一设置高度为100%*/
        height: 100%;
    }
    .el-header {
        background-color: #B3C0D1;
        color: #333;
        text-align: center;
        height: 80px !important;
    }

    .el-footer {
        background-color: #B3C0D1;
        color: #333;
        text-align: center;
        height: 26px !important;
    }
    .el-aside {
        background-color: #D3DCE6;
        color: #333;
        text-align: center;
        width: ;
    }

    .el-main {
        background-color: #E9EEF3;
        color: #333;
        text-align: center;
    }
</style>

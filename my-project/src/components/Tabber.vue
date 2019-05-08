<template>
    <div>
        <div class="tabsize">
            <div>1</div>
            <div>2</div>
            <div>3</div>
        </div>
    </div>
</template>
<script>
export default {
    data(){

    }
}
</script>
<style scoped>
    .tabsize{
        height:50px;
        width:100%;
        display: flex;
        position:absolute;
        bottom:0;
    }
    .tabsize div{
        flex:1;
    }
</style>

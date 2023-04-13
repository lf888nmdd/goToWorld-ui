<template>
    <div class="waterfall" >
        <slot>
            
        </slot>

    </div>
</template>
<script>
export default{
    name:'go-waterfall'
}
</script>
<style lang="scss" >
.waterfall{
    width: 100%;
    height: 100%;
    div{
        width: 50%;
        float: left;
        
    img{
            
            width: 98%;
            margin-left: 1%;
            margin-top: 1%;
        }
    }
}

</style>
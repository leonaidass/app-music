<template>
    <div>
          
    </div>
</template>

<script>
    export default {
        data() {
            return {
                selectItem:0,
                drawer:null,
                items:[
                    {icon:'fas fa-satellite-dish', text:'Discover'},
                    {icon:'fas fa-stream', text:'Stream'},
                    {icon:'fas fa-user', text:'Community'},
                    {icon:'fas fa-chart-pie', text:'Statistics'},
                ],
                collections:[
                    {icon:'fas fa-heart', text:'Likes', route:'/likes'},
                    {icon:'fas fa-heart', text:'Likes', route:'/likes'},
                    {icon:'fas fa-heart', text:'Likes', route:'/likes'},
                    {icon:'fas fa-heart', text:'Likes', route:'/likes'},

                ]
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>
<template>
    <div> Hello, {{user.firstName}} {{user.lastName}} de {{from}}!</div>
</template>

<script>
export default {
    data(){
        return{
            user:{
                firstName : 'Toshiro',
                lastName : 'Mugen',
            },
             from:'Japan'
        }
    }
}
</script>

<style>

</style>
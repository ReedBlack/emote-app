<template>
    <div>
        <h2>Your Common Emotes</h2>
    </div>
</template>

<script>
import * as d3 from 'd3'
export default {
    name: "BubbleData",
    data(){
        return {
            localAPI: 'http://localhost:3000/userdata',
            userData: []
        }
    },
    async mounted() {
    await fetch('http://localhost:3000/userdata')
        .then(res => res.json())
        .then(res => {
            
            this.userData = res.userdatas;
            console.log(this.userData)
        });
    }
}

</script>

<style>
    
</style>
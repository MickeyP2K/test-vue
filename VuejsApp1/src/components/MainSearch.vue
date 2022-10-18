<template>
    <div class="MainSearchBox">
        <input @input="changed" v-model="searchTerm" placeholder="Who do you want to speak to?"/>
    </div>
    <div class="MainSearchButton">
        <button @click="goSearch">Search!</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                //searchTerm = ''
            }
        },
        methods: {
            changed: function (event) {
                //alert(event.target.value)
            },
            goSearch: function (event) {
                console.log(this.searchTerm)
            }
        },
        watch: {
            /*// This is not working for some reason... Need to get back to the Vue doc I was using on the plane (on ipad) 
            searchTerm: function (newValue, oldValue) {
                console.log(newValue, oldValue)
            }*/
        }
    }
</script>

<style scoped>
</style>
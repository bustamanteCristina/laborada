<template>
    <div id = "header">
        <b-navbar toggleable="lg" type="dark" variant="primary">
        <b-navbar-brand id = "title" v-on:click="isHidden = !isHidden" >☰ EASAKAY</b-navbar-brand>
        </b-navbar>  
    </div>
</template>
<style>
    #title:hover{
        color: red;
    }
</style>
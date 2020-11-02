<template>
    <div id="app">
        <Navbar/>
        <router-view/>
        <Footer/>
    </div>
</template>

<style>
/*@import "assets/css/bootstrap.min.css";*/
@import "assets/css/font-awesome.css";
@import "assets/css/style.css";
</style>
<script>
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";

export default {
    components: {Navbar, Footer}
}
</script>
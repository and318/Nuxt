<template>
<b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#"><Logo /></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

        <b-navbar-nav class="ml-auto">

            <b-navbar-nav>
                
                <b-nav-item><NuxtLink to="/">Home page</NuxtLink></b-nav-item>
               
            </b-navbar-nav>
        </b-navbar-nav>
    </b-collapse>
</b-navbar>
</template>
<style>
.navbar {
    -webkit-box-shadow: 0px 9px 13px -6px rgba(0,0,0,0.75);
-moz-box-shadow: 0px 9px 13px -6px rgba(0,0,0,0.75);
box-shadow: 0px 9px 13px -6px rgba(0,0,0,0.75);
}
a { 
    color: white;
    }
a:hover {
        opacity: 0.8;
        color: white;
        text-decoration: none;
    }
</style>
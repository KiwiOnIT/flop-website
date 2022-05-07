<template>
<div class="navbar navbar-dark navbar-expand-lg bg-dark">
    <div class="container-fluid">
        <div>
            <a href="/">
                <img src="@/assets/logo.png" alt="" width="32" height="32">
            </a>
        </div>
        <div class="collapse navbar-collapse justify-content-end">
            <div class="navbar-nav">
                <router-link class="nav-link" to="/">
                    Home
                </router-link>
                <router-link class="nav-link" to="/about">
                    About
                </router-link>
                <router-link class="nav-link" to="/download">
                    Download
                </router-link>

            </div>
        </div>
    </div>
</div>
</template>

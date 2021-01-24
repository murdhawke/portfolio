
<template>
    <div id="navbar" >
        <template  >
            <b-navbar shadow is-fixed-top centered  id="nav-items">
                 <template #brand >
                    <b-navbar-item tag="router-link" :to="{ path: '/' }"  >
                        <img 
                            src="../assets/logo.png"
                            alt="Amos Cheruiyot"
                        >
                        <div id="name" class="is-large">
                            <h2>Amos Cheruiyot</h2>
                        </div>
                    </b-navbar-item>
                </template>
                <template #start >
                    <b-navbar-item tag="router-link" :to="{ path: '/about' }" >
                        About me
                    </b-navbar-item>
                    <b-navbar-item tag="router-link" :to="{ path: '/projects' }">
                        Projects
                    </b-navbar-item>
                    <b-navbar-item tag="router-link" :to="{ path: '/contact' }">
                        Contact
                    </b-navbar-item>
                </template>
            </b-navbar>
        </template>
    </div>
</template>

<script>
export default {
    
}
</script>

<style >
#nav-items a {
    padding-left: 5rem;
}
img {
    padding-right: 1rem;
}
</style>
<template>
    <div id="home">
        <section class="hero is-fullheight-with-navbar is-primary is-bold">
            <div class="hero-head"></div>
            <div class="hero-body">
                <div class="container">
                    <div class="columns">
                        <div class="column is-6 has-text-centered" id="home-title">
                            <h1 class="title is-size-1">Hi! <span style='font-size:50px;'>&#128075;</span></h1>
                            <h1 class="title is-size-2"> My name is Amos Cheruiyot</h1>
                            <br>
                            <h3 class="subtitle is-family-code">I build things and love tech.</h3>
                        </div>
                        <div class="column is-6" id="home-img">
                            <figure class="image is-256x256">
                                <img class="is-rounded" src="../assets/amos-1.jpg" alt="Amos Cheruiyot pic">
                            </figure>
                        </div>
                    </div>
                </div>
            </div>
            <span class="icon" shadow id="mail-icon">
                        <router-link to="/contacts">
                            <i class="far fa-envelope fa-2x"></i>
                        </router-link>
            </span>
           <div class="hero-foot" >
                <h3 id="copyright" class="has-text-centered"><i>Copyright &copy; 2021</i></h3>
                </div> 
        </section>
    </div>
</template>

<script>
export default {
    
}
</script>

<style >
#home-img {
    height: 300px;
    width: 300px;
}
#home-title {
padding-top: 3%;
margin-left: 10%;
}
#copyright {
    padding-bottom: 30px;
}
#home-btn {
    padding-top: 100px;
}
#mail-icon {
    position: absolute;
    left: 2%;
    bottom: 2%;
}
i {
    text-decoration: none;
    color: white;
}
</style>
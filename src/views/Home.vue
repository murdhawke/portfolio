<template>
    <div id="home">
        <section class="hero is-fullheight-with-navbar is-primary is-bold">
            <div class="hero-head"></div>
            <div class="hero-body ">
                <div class="container  ">
                    <div class="columns ">
                        <div class="column is-6 has-text-centered" id="home-title">
                            <h1 class="title is-size-1">Hi, <span style='font-size:50px;'>&#128075;</span></h1>
                            <h1 class="title is-size-2"> I`m Amos Cheruiyot!</h1>
                            <br>
                            <h3 class="subtitle is-family-code">I build things and love tech.</h3>
                        </div>
                        <div class="column is-6" id="home-img">
                            <figure class="image is-256x256">
                                <img class="is-rounded" src="../assets/amos-1.jpg" alt="Amos Cheruiyot pic">
                            </figure>
                        </div>
                    </div>
                    <div class="socials container">
                        <div class="columns has-text-centered">
                            <div class="column is-8">
                                <span class="icon is-large">
                                    <a href="https://www.linkedin.com/in/murdhawke/" target="_blank">
                                        <i class="fab fa-linkedin-in fa-lg"></i>
                                    </a>
                                </span>
                                <span class="icon is-large">
                                    <a href="https://github.com/murdhawke" target="_blank">
                                        <i class="fab fa-github fa-lg"></i>
                                    </a>
                                </span>
                                <span class="icon is-large">
                                    <a href="https://codepen.io/murdhawke" target="_blank">
                                        <i class="fab fa-codepen fa-lg"></i>
                                    </a>
                                </span>
                                <span class="icon is-large">
                                    <a href="https://stackoverflow.com/users/5805468/amos-cheruiyot" target="_blank">
                                        <i class="fab fa-stack-overflow fa-lg"></i>
                                    </a>
                                </span>
                            </div>
                            <div class="column is-4"></div>
                        </div>
                    </div>
                </div>
            </div>
           <div class="hero-foot" >
                    <span class="icon" id="mail-icon">
                        <router-link to="/contacts">
                            <i class="far fa-envelope fa-2x"></i>
                        </router-link>
                    </span>
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
    position: relative;
    margin-left: auto;
    margin-right: auto;
}
#home-title {
padding-top: 3%;
margin-left: 10%;
}
#copyright {
    padding-bottom: 20px;
}
#mail-icon {
    margin-right: auto;
    margin-left: 50px;
    margin-bottom: 1;
    float: left;
}
i {
    text-decoration: none;
    color: white;
}
.socials {
    padding: 0;

}
</style>
<template>
    <div id="projects">
        <section class="hero is-fullheight-with-navbar is-primary is-bold">
                <h2 class="title has-text-centered"> My Projects</h2>
                <div class="projectlayout">
                    <ProjLayout></ProjLayout>
                </div>
        </section>
            <Footer></Footer>
    </div>
</template>

<script>
import Footer from '../components/Footer'
import ProjLayout  from '../components/projLayout'
export default {
    components: { Footer, ProjLayout}
    
}
</script>

<style >
.title {
    padding-top: 50px;
}
.hero {
    padding-bottom: 50px;
}
.projectlayout {
   padding: 50px;
}
</style>
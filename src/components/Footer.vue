<template>
    <div id="footer">
        <div class="columns is-mobile">
            <div class="column">
                <ul>
                    <li>Home</li>
                    <li>Projects</li>
                    <li>About</li>
                </ul>
            </div>
            <div class="column">
                <ul>
                    <li>Privacy Policy</li>
                    <li>Contacts</li>
                    <li>Location</li>
                    <li>News Feed</li>
                </ul>
            </div>
            <div class="column">
                <ul>
                    <li>Maps</li>
                </ul>
            </div>
            <div class="column">
                <ul>
                    <li>Codepen</li>
                    <li>Stack Overflow</li>
                    <li>Github</li>
                    <li>LinkedIn</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.columns {
    background-color: white;
    height: 200px;
    padding: 50px;
}
.column {
color:black;
margin: auto;
padding-left: 100px;
}
li {
    list-style: none;
    padding-top: 20px;
}
</style>
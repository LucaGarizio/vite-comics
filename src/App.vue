<script>
import AppHeader from './components/AppHeader.vue'
import MainContent from './components/MainContent.vue'
import Shop from './components/Shop.vue'
import Info from './components/Info.vue'
import Social from './components/Social.vue'

export default{
    components:{
        AppHeader,
        MainContent,
        Shop,
        Info,
        Social
    }
}
</script>

<template>
    <header>
        <AppHeader/>
    </header>

    <main>
        <!-- main content -->
        <section>
            <MainContent/>
        </section>

        <!-- section shop -->
        <section>
            <Shop/>
        </section>
    </main>

    <footer>
        <Info/>

        <Social/>
    </footer>
</template>

<style lang="scss">
// @use'.styles/partials/variables' as *;
// @use '.styles/general/scss' as *; 
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

    body{
        background-color: black;
    }
</style>

<script>
import NavBar from './components/Navbar.vue'
import Jumbo from './components/Jumbo.vue'
import MainContent from './components/MainContent.vue'
import Shop from './components/Shop.vue'
import Info from './components/Info.vue'
import Social from './components/Social.vue'

export default{
    components:{
        NavBar,
        Jumbo,
        MainContent,
        Shop,
        Info,
        Social
    }
}
</script>

<template>
    <header>
        <NavBar/>
        <Jumbo />
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
        <section>
            <Info/>
        </section>

        <section>
            <Social/>
        </section>
    </footer>
</template>

<style lang="scss">
@use './styles/partials/variables' as *;
@use './styles/general.scss' as *; 
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
    body{
        background-color: #333;
    }
</style>

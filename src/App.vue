<script>
import Header from './components/Header.vue'
import MainContent from './components/MainContent.vue'
import Shop from './components/Shop.vue'
import Info from './components/Info.vue'
import Social from './components/Social.vue'

export default{
    components:{
        Header,
        MainContent,
        Shop,
        Info,
        Social
    }
}
</script>

<template>
    <header>
        <Header/>
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
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

    body{
        background-color: black;
    }
</style>

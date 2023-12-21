<script>
import Header from './components/Header.vue'
import MainContent from './components/MainContent.vue'
import Shop from './components/Shop.vue'

export default{
    components:{
        Header,
        MainContent,
        Shop
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
            <Shop/>ß
        </section>
    </main>

    <footer>

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

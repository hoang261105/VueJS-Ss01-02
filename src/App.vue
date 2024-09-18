<template>
  <div>
    <!-- Bài 1 -->
    <B1 />
    <br />
    <!-- Bài 2 -->
    <B2 />
    <br />
    <!-- Bài 3 -->
    <B3 />
    <br />
    <!-- Bài 4 -->
    <B4 />
    <br />
    <!-- Bài 5 -->
    <B5 />
    <br />
    <!-- Bài 6 -->
    <B6 />
    <br />
    <!-- Bài 7 -->
    <div class="home">
      <Header />
      <div class="between">
        <Menu />
        <div class="main-footer">
          <Main />
          <Footer />
        </div>
      </div>
    </div>
    <br />
    <!-- Bài 8 -->
    <div class="home">
      <Headers />
      <Navbar />
      <div class="body">
        <Menu2 />
        <Cart />
        <Article />
      </div>
    </div>
    <br />
    <!-- Bài 9 -->
    <B9 />
    <br />
    <!-- Bài 10 -->
    <B10 />
  </div>
</template>

<script setup>
import B1 from "./components/B1.vue";
import B2 from "./components/B2.vue";
import B3 from "./components/B3.vue";
import B4 from "./components/B4.vue";
import B5 from "./components/B5.vue";
import B6 from "./components/B6.vue";
import Header from "./components/B7/Header.vue";
import Menu from "./components/B7/Menu.vue";
import Main from "./components/B7/Main.vue";
import Footer from "./components/B7/Footer.vue";
import Headers from "./components/B8/Header.vue";
import Navbar from "./components/B8/Navbar.vue";
import Menu2 from "./components/B8/Menu.vue";
import Cart from "./components/B8/Cart.vue";
import Article from "./components/B8/Article.vue";
import B9 from "./components/Manager.vue";
import B10 from "./components/TodoList.vue";
</script>

<style>
.between {
  display: flex;
}

.main-footer {
  width: 85%;
  background: rgb(210, 210, 210);
  padding: 30px;
  height: 90vh;
}

.body {
  display: flex;
  justify-content: space-between;
}
</style>

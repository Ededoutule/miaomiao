<template>
  <div>
    <div id="main">
      <Header title="登陆喵喵"></Header>
      <Login></Login>
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
import Login from "@/components/Login";
export default {
  name: "Mine",
  components: {
    // eslint-disable-next-line vue/no-unused-components
    Header,
    // eslint-disable-next-line vue/no-unused-components
    Footer,
    // eslint-disable-next-line vue/no-unused-components
    Login
  }
};
</script>

<style lang="stylus" scoped></style>

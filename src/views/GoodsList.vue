<template>
  <div>
    <nav-header></nav-header>
    <nav-bread>
      <span slot="bread">Goods</span>
    </nav-bread>
    <nav-footer></nav-footer>
  </div>
</template>
<script>
  import './../assets/css/base.css'
  import './../assets/css/product.css'
  import NavHeader from './../components/NavHeader.vue'
  import NavFooter from './../components/NavFooter.vue'
  import NavBread from './../components/NavBread.vue'

  export default {
    data() {
      return {msg: 'hello vue'}
    },
    components: {
      NavHeader: NavHeader,
      NavFooter: NavFooter,
      NavBread: NavBread
    }
    //components: {'other-component': OtherComponent, HeaderComponent,}
  }</script>

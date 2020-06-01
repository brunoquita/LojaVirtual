<template>
  <section>
    <h1> Compre ou Venda</h1>
    <ProdutosBuscar/>
    <ProdutosLista/>
  </section>
</template>

<script>
import  produtosBuscar from "@Components/produtosBuscar.vue";
import  produtosLista from "@Components/produtosLista.vue";

export default {

  name: 'Home',
  components:{
   "ProdutosBuscar": ProdutosBuscar,
    "ProdutosLista":ProdutosLista
  }
 
}
</script>

<style  scoped>
 h1{
   font-size: 2rem;
   color: #87f;
   margin-top: 40px ;
   text-align: center;
 }
</style>
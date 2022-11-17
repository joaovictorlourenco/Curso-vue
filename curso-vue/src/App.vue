<template>
    <NavBar/>
</template>

<script>
// Assim que se importa um componente de vue
import NavBar from '@/components/NavBar'

export default {
    // Aqui estou exportando o componente que estou
   name:'App',
    //Aqui chamo o componente que estou importando
   components:{
    NavBar
   }
}
</script>

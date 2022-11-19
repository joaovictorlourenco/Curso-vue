<template >
    <NavBar/>
    <firstSection/>
</template>

<script>
// Assim que se importa um componente de vue
import NavBar from '@/components/NavBar'
import firstSection from '@/components/firstSection.vue'
// import LifeCicle from './components/LifeCicle.vue'

export default {
    // Aqui estou exportando o componente que estou
   name:'App',
    //Aqui chamo o componente que estou importando
   components:{
    NavBar,
    firstSection
    // LifeCicle
   }
}
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100;200;300;400;500;600;700;800;900&display=swap');
    *{

        margin: 0;
        padding: 0;
        box-sizing: border-box;

    }
    li{

        list-style-type: none;

    }
    a{

        text-decoration: none;

    }
    body{

        background-color: #303030;

    }
    html{

        font-family: 'Roboto slab', sans-serif;

    }

</style>

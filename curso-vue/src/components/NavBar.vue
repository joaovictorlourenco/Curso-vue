<template>
    <div class="navbar">
        <a href=""></a>
        <nav>
            <ul class="elements">
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'NavBar',
    data() {
        return{
           home: 'Home',
           sobre: 'Sobre'
        }
    }
}
</script>


<style scoped>

    .navbar{

        width: 100%;
        height: 100px;

    }

    .elements{

        display: flex;
        gap: 2rem;
        font-size: 1.4rem;
        align-items: center;
        justify-content: center;
        padding: 1rem;
        
    }

    a{
        color:#ffff;
    }

    a:hover{
        transition-duration: 500ms;
        color: #FFA500; 
    }
  

</style>


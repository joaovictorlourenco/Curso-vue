<template>
    <div class="container">
        <div class="card">
            <div class="img-div"></div>
            <h2>{{ nome}}</h2>
        </div>
    </div>
</template>

<script>
export default {
    name: 'firstSection',
    data() {
        return{
           nome:'João Victor'
           
        }
    }
}
</script>
<style scoped>

.container{

    width: 100%;
    height: calc(100vh - 100px);
    display: grid;
    place-content: center;

}

.card { 
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap: 2rem;
    width: 300px;
    height: 360px;
    background-color: #212121;
    box-shadow: 15px 15px 30px #191919,
                -15px -15px 30px #292929;
    transition: border-radius cubic-bezier(0.075, 0.82, 0.165, 1) 1s,
                transform cubic-bezier(0.075, 0.82, 0.165, 1) 1s;
}
.img-div{

    width: 100px;
    height: 100px;
    border: 1px solid #FFA500;
    border-radius: 50%;

    /* Shadow box */
    box-shadow: 0px 0px 56px -14px rgba(255,184,0,1);
    -webkit-box-shadow: 0px 0px 56px -14px rgba(255,184,0,1);
    -moz-box-shadow: 0px 0px 56px -14px rgba(255,184,0,1);
    /* Colocando background */

    background-image: '@/assets/avatar.png';

}


h2{
    color: white;
    margin: 0 auto;
}

h2:hover{
    transition-duration: 500ms;
    color: #FFA500; 
}

.card:hover {
    border-bottom-right-radius: 50px;
    border-top-left-radius: 50px;
    transform: scale(1.05);
}

</style>
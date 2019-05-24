<template>
    <div class="welcome">
        <div class="welcome__heading">
             <h1>Hello !</h1>
        </div>
        <vue-typer text="My name is Matt and I'm Junior Front-end developer"></vue-typer><br/>
        <button>Learn More</button>
    </div>
</template>
<script>
import { VueTyper } from 'vue-typer';

export default {
    components:{
        'vue-typer': VueTyper
    }
}
</script>

<style lang="scss">
.welcome{
    background-image: url("../assets/Main.jpg");
    filter:brightness(75%);
    width: 100%;
    height:95vh;
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Do not repeat the image */
    background-size: cover;
    color: #eee;
    font-size:3rem;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

    &__heading{
        filter: brightness(100%);
        display: flex;
        align-items: flex-start;
        margin-right: 2rem;
    }
}

vue-typer{
    display: block;
  
font-size: 3rem;
font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}

.custom.char.typed{
        color:white;
    }

</style>

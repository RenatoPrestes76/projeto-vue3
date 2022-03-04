<template>
 <div id="horarioDia"> 
    <div id="horario"> 
        <h1>00:00</h1>
    </div>
    <div id="Dia"> 
        <p>terça-feira, 17 de março de 2020 </p>
    </div>
</template>

<script>
export default function logicalTimer(){

    const $ = document.querySelector.bind(document)
    const segundos = $("#time-box")
    let contador = 600
    
    setInterval(() => {
        segundos.textContent = contador
        contador--
        if(contador === 0){
            // history.pushState(null, "Login - Compass", "https://renatoprestes76.github.io/ProjetoCompassUol1")
            window.location.reload() //window é a janela, location é local, reload é retorne a janela local//
        }
    },1000)
}
};
</script>
<style lang="scss" scoped>
@import '@/components/timer/index.scss';
</style>

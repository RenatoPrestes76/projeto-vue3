<template>
            <div class="text-ola" id="text-ola">
                <img  id="midiaLogoCompass" draggable="false" src='@/assets/LogoCompassText.png' alt="imagem-compass">
                <div id="containerText">
                    <div id="text">
                        <h2>Olá,</h2>
                        <p id="frase-login">Para continuar navegando de forma<br> segura, efetue o login na rede.</p>
                        <h1>Login</h1>
                    </div>
                    <div id="containerImput">               
                        <div id="textInput" class="imput">
                            <div class="test">
                                    <input autocomplete="off" type="text" id="user" class="input" placeholder="Usuário">
                                <img  draggable="false" src="@/assets/login.png">
                            </div>
                        </div>
                        <div id="passwordInput" class="imput">
                            <div class="test">
                                <input autocomplete="off" type="password" id="password" class="input" placeholder="Senha">
                                <img  draggable="false" src="@/assets/password.png">
                            </div>
                        </div>
                        <div id="textErro">
                            <p>Ops, usuário ou senha inválidos.<br> Tente novamente!</p>
                        </div>
                        <div id="buttonLogin">
                            <button>Continuar</button>
                        </div>
                    </div> 
                </div>
            </div>     
</template>

<script>
export default {
  name: 'Login-page',
};
</script>

<style lang="scss" scoped>
@import '@/containers/Login/index.scss';
</style>

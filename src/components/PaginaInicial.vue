<template>
    <header class="header">
       <div class="logo">
        <img src="../assets/logo_ong.png" alt="" class="logo_img">
        <p>Apoio Solidário</p>
       </div>

        <ul class="lista">
            <li>Início</li>
            <li>Campanhas</li>
            <li>ONGs</li>
            <li>|</li>
            <li>Sou uma ONG</li>
            <li><button>Apoiar</button></li>
        </ul>
    </header>
    <div class="informacao">
        <div class="conectando_ongs">
            <h1 class="titulo">Conectando ONGs e pessoas para doações e apoio.</h1>
            <div class="buttom">
                <button class="apoiar">apoiar</button>
                <button class="sobre_nos">sobre o Projeto</button>
            </div>
        </div>
        <div class="imagem">
            <img src="../assets/Ilustracoes.png" alt="" class="ilustracao">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
*{
    font-family: sans-serif;
}
.titulo{
    font-size: 69px;
    background: linear-gradient(to bottom, #42A3DA, #559A63);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}
.ilustracao{
    width: 500px;
}
.apoiar{
    color: #ffffff;
    width: 150px;
    height: 50px;
    background-color: #00a2ff;
    border-radius: 10px;
    margin-right: 20px;
}
.sobre_nos{
    color: #42A3DA;
    width: 150px;
    height: 50px;
    background-color: #42a2da00;
    border: 2px solid #42A3DA;
    border-radius: 10px; 
    margin-left: 20px;
}
.conectando_ongs{
    display: flex;
    margin-left: 80px;
    justify-content: center;
    flex-direction: column;
    width: 50%;
}
.imagem{
    margin-top:40px;
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding-left: 35px;
}
.informacao{
    width: 100%;
    display: flex;
}
.logo{
    justify-content: center;
    align-items: center;
    display: flex;
    font-size: large;
    gap: 10px;
    width: 200px;
}
.header, li{
    list-style-type: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo_img{
    width:45px;
    height:45px;
}
.lista{
    font-weight:600 ;
    font-size:  15px;
    color: #42A3DA;
    display: flex;
    gap: 23px;
}
button{
    cursor: pointer;
    font-weight:600;
    font-size: 15px;
    border: none;
    width: 110px;
    height: 30px;
    color: white;
    background-color: #42A3DA;
    border-radius: 5px;
}

</style>
<script>

export default {
    name: 'Parte3'
}

</script>

<template>
    <div class="main">

        <div class="titulo">
            CONHEÇA NOSSOS SERVIÇOS
        </div>

        <div class="subtitulo">
            Explore a excelência em design de unhas com nossa gama de produtos premium e serviço personalizado na Rachel
            Costa.
        </div>

        <div class="servico">
            <div class="conteudo">
                <div class="imagem">
                    <img class="imagem_servico" src="../assets/imagens/94e78e70e1bbee751da2f9e591f6fae9.jpg" alt="">
                </div>
                <p>Manicure</p>
                <div class="descricao">
                    descrição do serviço
                </div>
            </div>
            <div class="conteudo">
                <div class="imagem">
                    <img class="imagem_servico" src="../assets/imagens/94e78e70e1bbee751da2f9e591f6fae9.jpg" alt="">
                </div>

                <p>Acri Gel</p>
                <div class="descricao">
                    descrição do serviço
                </div>
            </div>
        </div>
        <div class="servico">
            <div class="conteudo">
                <div class="imagem">
                    <img class="imagem_servico" src="../assets/imagens/94e78e70e1bbee751da2f9e591f6fae9.jpg" alt="">
                </div>
                <p>Manicure</p>
                <div class="descricao">
                    descrição do serviço
                </div>
            </div>
            <div class="conteudo">
                <div class="imagem">
                    <img class="imagem_servico" src="../assets/imagens/94e78e70e1bbee751da2f9e591f6fae9.jpg" alt="">
                </div>

                <p>Acri Gel</p>
                <div class="descricao">
                    descrição do serviço
                </div>
            </div>
        </div>
        <div class="servico">
            <div class="conteudo">
                <div class="imagem">
                    <img class="imagem_servico" src="../assets/imagens/94e78e70e1bbee751da2f9e591f6fae9.jpg" alt="">
                </div>
                <p>Manicure</p>
                <div class="descricao">
                    descrição do serviço
                </div>
            </div>
            <div class="conteudo">
                <div class="imagem">
                    <img class="imagem_servico" src="../assets/imagens/94e78e70e1bbee751da2f9e591f6fae9.jpg" alt="">
                </div>

                <p>Acri Gel</p>
                <div class="descricao">
                    descrição do serviço
                </div>
            </div>
        </div>


        <div class="btn">
            WHATSAPP
        </div>

    </div>
</template>

<style scoped>
.main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.titulo {
    color: #f3f3f3;
    font-size: 2rem;
    font-weight: 1000;
    text-align: center;
    padding: 4%;
}

.subtitulo {
    color: #f3f3f3;
    font-size: 1rem;
    font-weight: 500;
    letter-spacing: 1.5px;
    line-height: 1.2rem;
    text-align: center;
    padding: 5%;
}

.imagem {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.imagem_servico {
    width: 50%;
    border-radius: 20%;
    box-shadow: 0 0 20px 1px #f3f3f3;
}

.servico {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}

.conteudo {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

p {
    color: #f3f3f3;
    font-size: 1.2rem;
    padding: 3%;
    margin-top: 3%;
}

.descricao {
    color: #f3f3f3;
    margin-bottom: 10%;
}

.btn {
    background-color: #fff;
    font-size: 1rem;
    font-weight: bolder;
    padding: 3%;
    border: 2px solid #cc586b;
    border-radius: 20px;
    color: #cc586b;
}
</style>
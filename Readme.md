<h1 align="center">Producer de carro</h1>

  <p align="center">O projeto foi feito acompanhando a lista  <a href=https://www.youtube.com/playlist?list=PLIBLotuIrOQYQQFAXx2s-sR_GE4eErNuS>Kafka </a> sobre
   Kafka.</p>


<p> O projeto é um producer o consumer pode ser gerado pelo Conduktor ou no seu <a href="https://github.com/iagoAguiar/consumerKafka">Consumer</a>.</p>

<p>Foi escolhido enviar um objeto por ser mais próximo do que realmente é feito pelas empresas, o modelo de objeto enviado é um Json: </p>

```shell
{
    "model" : "testando1234",
    "color" : "2434523"
}
```

<p>Foi alterada a porta padrão desse projeto, para ele rodar em paralelo com seu Consumer, ele está rodando na porta 8081.</p>

  

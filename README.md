
# Utilizando APIS - Cap 10

![enter image description here](https://raw.githubusercontent.com/llmdev/cap10-consumindo-api/master/assets/Capturar.PNG)

Utilizamos apis do google maps para criar uma rota de como chegar até o parceiro do site gulliver.

## APIS
### Geocoding do google maps

Utilizamos esta api para gerar o PLACE-ID do usuario, qual seria o seu numero de identificacao no google maps, pegamos o CEP digitado pelo usuario e enviamos uma requisicao HTTP para api no qual nos retorna o place id

link: https://developers.google.com/maps/documentation/geocoding/overview

### Google Maps Embed API

Utilizamos a api de embed google maps para criar o mapa com a rota do usuario ate o local destino de nosso parceiro, com o resultado do Geocoding atualizamos o iframe com a url correta para gerar a rota em tela.

link: https://developers.google.com/maps/documentation/embed/get-started


Igor Simões Fugiwara, Lucas Lopes de Moura, Paulo Cesar Pereira Demutti




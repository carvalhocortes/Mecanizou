# Mecanizou

Para atender ao teste da entrevista da Mecanizou criei uma API REST que roda em um Docker seguindo o que foi requisitado.

# Antes de testar

Foi enviado um arquivo .env no e-mail. este deve ser salvo na raiz do diretório (junto ao package.json).
Não compartilhar a chave da API.

# Para executar o Docker

Para instalar o Docker acessar o site abaixo:

[https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

No terminal

```SH
docker-compose up --build
```

# Para testes

[Aqui](https://1drv.ms/u/s!AtX-17N2_QZap7Yh_1joLQgNNLb8Mw?e=E4rK3E) temos arquivos do postman para realizar os testes da API.

# Documentação

A documentação foi feita utilizando padrão opemApi e com a biblioteca Redocly.

Primeiro passo é fazer o build.

```SH
node rum docs
```

Será salvo na raiz do projeto um arquivo `redoc-static.html` que conterá toda documentação.

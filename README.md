#### Front LojaCorePlan

#### Funcionalidade
Este front foi moldado para consumir a api presente no repositorio api_loja_coreplan de admnistração de produtos de uma loja ficticia, sendo possivel criar, editar e excluir produtos e ofertas. Para mais informações acesse: https://github.com/joaovitornunes09/api_loja_coreplan

##### Sobre tecnologias utilizadas nesse projeto:

- React 18.2.0
- Docker 24.0.2

## Instalação

##### Requisito obrigátorios
Antes de tudo você precisa ter o docker e o docker-compose e também o git.
Caso não tenha instalado, aqui alguns links de referência:
- Aqui encontrar os passos para instalação do Docker => https://docs.docker.com/get-docker/ 
- Aqui encontrar os passos para instalação do Docker Compose => https://docs.docker.com/compose/ 
- Aqui encontrar os passos para instalação do git => https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

##### Clone o projeto
Com o git instalado e em um diretório da sua escolha, baixe o projeto:

```sh
git clone https://github.com/joaovitornunes09/front_loja_coreplan.git
```

##### Instalação de pacotes e Docker:

Para instalar esta aplicação basta vc rodar o comando abaixo:

```sh
docker-compose up -d --build
```

Se tudo ocorrrer como o planejado espere alguns segundos a aplicação ja estará rodando

Url: http://localhost:1008/

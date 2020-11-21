<p align="center">
  <a href="https://konghq.com/kong/" target="blank"><img src="https://miro.medium.com/max/1020/1*gjFEvJt_18hI5Sk39fL2nQ.png" width="320" alt="Kong Logo" /></a>
</p>

kong-http-https
=========================
* Esse repositório contém um arquivo docker-compose para intalação completa e inegração com requisições http e https.
* Para requisições http utilizar a porta 8000.
* Para requisições https utilizar a porta 8443.

## Sumário
* [Começando](#começando)
* [Pré-requisitos](#Pré-requisitos)
* [Instalando](#Instalando)
* [Estrutura de código](#Padronização-de-codigo)

## Começando

### Pré-requisitos

* kong
* konga

### Instalando

Clonar o repositório
```
git clone https://github.com/vitorbgouveia/kong-http-https.git
```

Adicione os certificados no caminho kong-http-htttps/kong-https/certs.

Execute o comando:
```
docker-compose up
```

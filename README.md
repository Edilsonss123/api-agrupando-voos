<p align="center">
    <img src="https://raw.githubusercontent.com/Edilsonss123/teste123milhas/main/resources/img/teste123Milhas.png" width="600" height="300">
</p>

# API agrupando voos Back-end

 Projeto com o objetico consumir e disponibilar dados através de API padrão REST.
 Projeto feito com uso da framework Laravel.

## Pré-requisitos 

- PHP v7.4.13 ou superior [documentation](https://www.php.net/downloads.php)
- Laravel v8.22.1 [documentation](https://laravel.com/docs)

## Aplicação

- Host: [teste123milhas.herokuapp.com](http://teste123milhas.herokuapp.com)
- GET: [/api/flight/search](http://teste123milhas.herokuapp.com/api/flight/search) -> Lista todos os voos disponíveis
- GET: [/api/flight/search/group](http://teste123milhas.herokuapp.com/api/flight/search/group) -> Lista os voos agrupados por tarifa e nos valores dos voos de ida/volta

## Rotas e chamadas Postman

 - [Documentação API Postman](https://documenter.getpostman.com/view/5807678/TVzVivkw)

## Setting Up a Project 

Clone este repositório

```
git clone https://github.com/Edilsonss123/teste123milhas.git teste123milhas
```
Acesse a pasta do projeto no terminal/cmd

```
cd teste123milhas
```

Instalando dependência 

```
composer install
```

Gerando chave do projeto

```
php artisan key:generate 
```

Iniciando servidor projeto

```
php artisan serve --port=2021
```
O servidor inciará na porta informada :2021 - acesse com o navegador ``` http://localhost:2021```

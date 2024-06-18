<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://getcomposer.org/img/logo-composer-transparent.png" alt="Project logo"></a>
</p>

<h3 align="center">Projeto sobre Composer <br><h4 align="center">(Desenvolvido durante o curso da Alura sobre Composer)</h4></h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/AguiarDG/composer)](https://github.com/AguiarDG/composer/issues)

[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/AguiarDG/composer)](https://github.com/AguiarDG/composer/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> O projeto Buscador de Cursos foi desenvolvido para retornar os cursos cadastrados no sites da Alura
    <br> 
</p>

## 📝 Menu de Conteudo

- [Sobre](#sobre)
- [Introdução](#introducao)
- [Teste automatizado](#test)
- [Modo de Usar](#usage)
- [Utilizados para construção](#built_using)
- [Autor](#authors)
- [Fonte de conhecimento](#acknowledgement)

## 🧐 Sobre <a name = "sobre"></a>

O projeto Buscador de Cursos foi desenvolvido para treinar o que foi aprendido durante o curso, o projeto retorna os cursos cadastrados no sites da Alura, a busca é feita baseada na URL adicionada no codigo.

## 🏁 Introdução <a name = "introducao"></a>

Segue algumas instruções o você precisa ter e fazer para instalar, baixar o projeto e instalar o que foi desenvolvido.

### Pré-requisitos

Você precisa ter instalado:

```
- PHP
- Composer
```

## 🔧 Teste automatizado <a name = "tests"></a>

Segue o comando abaixo para rodar o teste automatizado utilizando o PHPUnit, no qual verifica se o resultado da requisição esta correta

```
composer test
```

### Outros pacotes e comandos utilizados

O pacote já inclui o pacote phan e o php_codesniffer para verificar se o código esta nos padrões definidos, segue os comandos para utilização:

```
composer cs
composer phan
```

Criei um comando para executar as 3 verificação:

```
composer check
```

## 🎈 Modo de Usar <a name="usage"></a>

Para rodar esse pacote em seu projeto basta utilizar o comando do php

```
php buscarCursos.php
```

## ⛏️ Utilizados para construção <a name = "built_using"></a>

- [Composer](https://getcomposer.org) - Tool for dependency management in PHP
- [Guzzle](https://packagist.org/packages/guzzlehttp/guzzle) - HTTP client library
- [symfony/dom-crawler](https://packagist.org/packages/symfony/dom-crawler) - Eases DOM navigation for HTML and XML documents
- [symfony/css-selector](https://packagist.org/packages/symfony/css-selector) - Converts CSS selectors to XPath expressions

## ✍️ Autor <a name = "authors"></a>

- [@AguiarDG](https://github.com/aguiardg)


## 🎉 Fonte de conhecimento <a name = "acknowledgement"></a>

- Alura - Curso de Composer

<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="TCC" />

  &#xa0;

  <!-- <a href="https://mon.netlify.app">Demo</a> -->
</div>

<h1 align="center">Trabalho de Conclusão de Curso</h1>

<p align="center">
  <img alt="Involved languages" src="https://img.shields.io/github/languages/top/draylon/tcc_impl?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/draylon/tcc_impl?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/draylon/tcc_impl?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/draylon/tcc_impl?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/draylon/mon?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/draylon/mon?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/draylon/mon?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Mon 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#ship-navigate">Navigate</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#sparkles_descritivo">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/draylon" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

Implementação da solução presente no trabalho de conclusão de curso de Ciência da Computação.

Este repositório contém software de sensoreamento baseado em Arduino C, desenvolvido com [hardware ESP32 LoRa](https://resource.heltec.cn/download/Manual%20Old/WiFi%20Lora32Manual.pdf), e tem o objetivo de estabelecer uma rede LoRa em topologia estrela, utilizando dispositivos "Node" como "Gateways".
[A API](https://github.com/Draylon/tcc_api) é responsável por unir sensoreamento e usuários do sistema, bem como armazenar dados provenientes da rede LoRa e do processamento de seus dados.
As aplicações de visualização dos dados desta solução são desenvolvidos em [React](https://react.dev/) e [Flutter](https://flutter.dev/), com finalidades de Aplicação WEB e Apllicação MOBILE respectivamente.

## :ship: Navigate ##

Repositórios individuais

- [ESP32 LoRa](https://github.com/Draylon/tcc_lora_impl)
- [API](https://github.com/Draylon/tcc_api)
- [WEBAPP](https://github.com/Draylon/tcc_api_webapp)
- [FLUTTER](https://github.com/Draylon/tcc_flutter_ui)

## :sparkles: Features ##

:heavy_check_mark: Sensoreamento de longo alcance;\
:heavy_check_mark: Implantação simplificada;\
:heavy_check_mark: Frameworks de trabalho para WEB e Mobile;



## :checkered_flag: Starting ##

```bash
# Git clone nesse projeto
$ git clone https://github.com/Draylon/tcc_impl

# Acessar o repositório local do projeto
$ cd tcc_impl

# Instalar os submódulos
$ git submodule update --init
ou
$ git pull --recurse-submodules

# Atualizar módulos para releases mais atuais
$ git submodule update --remote --merge
```

## :sparkles: Descritivo

Este projeto consiste em uma solução de 3 frentes, estendendo todas as fases da arquitetura de uma implementação de sensoreamento, sendo estas: 

- Física / Sensoreamento
- API / Centralização
- Interface / Visualização



## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/draylon" target="_blank">Draylon</a>

&#xa0;

<a href="#top">Back to top</a>

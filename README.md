<p align="center">
    <a href="https://www.linkedin.com/in/brunofamiliar/">
        <img src="./src/assets/logo.png" width="150px">
    </a>
</p>

[![Author](https://img.shields.io/badge/author-brunofamiliar-green?style=for-the-badge&logo=github)]('https://github.com/brunofamiliar')
![GitHub Repo stars](https://img.shields.io/github/stars/brunofamiliar/photus?color=green&style=for-the-badge)

## 💡 Informações
Esse é um componente Vuejs de galeria de fotos adaptado para a biblioteca [Photus](https://github.com/brunofamiliar/photus/).

>⚠️ Esse projeto está em fase beta, por esse motivo não deve ser usado no ambiente de produção

## 📗 Requerimento
<div>
    <ul>
         <li>Tenha o <a href="https://www.npmjs.com/get-npm">NPM e NodeJS</a> instalado em seu sistema.</li> 
</ul>
</div>

## 🛠️ Como utilizar
1. Realizar a instalação
```bash
$ npm install vuellery
```
2. Faça a importação e utilize

```
<template>
    <vuellery></vuellery>
</template>

<script>
import Vuellery from 'vuellery';

exports default {
    [...]
    components: {
        Vuellery
    }
    [...]
}
</script>
```

## ⚙️ Configurações disponíveis
O componente vuellery recebe como parâmetro todas as opções que a biblioteca [Photus](https://github.com/brunofamiliar/photus#%EF%B8%8F-configura%C3%A7%C3%B5es-dispon%C3%ADveis) disponibiliza, sendo atualizado periodicamente. Basta passar as opções desejada através da prop <strong><i>options</i></strong>.

```
<template>
    <vuellery :options={...options}></vuellery>
</template>

<script>
import Vuellery from 'vuellery';

exports default {
    [...]
    components: {
        Vuellery
    },
    data() {
        return {
            options: {
                [your options]
            }
        }
    }
    [...]
}
</script>
```
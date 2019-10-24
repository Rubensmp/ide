# Coding Blocks IDE

Coding Blocks IDE é uma IDE online que suporta compilaçoes de várias linguagens de programação.

## Desenvolvimento

[![Netlify](https://www.netlify.com/img/global/badges/netlify-color-accent.svg)](https://app.netlify.com/sites/cb-ide)

Commits para master e PRs são automaticamente compilado e implementado pela Netlify.

![image](https://user-images.githubusercontent.com/22571395/40135873-ffe73618-5963-11e8-85db-01c103688f4a.png)

## README traduzido para:

- [English](README.md)
- [Brazilian Portuguese](docs/br/README.md)

## Índice

- [Build Setup](#build-setup)
- [Funcionalidades](#features)
- [Funções](#functions)
- [API](#api)

## Build Setup

```bash
# instalar dependências
npm install

# serve com hot reload em localhost:8080
npm run dev

# build para produção com minificação
npm run build

# build para produção e vizualiza o relatório da analise do bundle
npm run build --report
```

Para mais detalhes em como as coisas funcionam, verifique o [guia](http://vuejs-templates.github.io/webpack/) e a [documentação do vue-loader](http://vuejs.github.io/vue-loader).

## Funcionalidades

Esse editor e compilador de código online responsivo possui as seguintes funcionalidades.

| Funcionalidade                      | Detalhes                                                                                                                                                                                                              |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Suporte para várias linguagens**  | C, C++, Java, Python, Java Script.                                                                                                                                                                                    |
| **Upload de código**                | É possível fazer upload do sistema local.                                                                                                                                                                             |
| **Download de código**              | É possível fazer o download com o nome especificado pelo usuário.                                                                                                                                                     |
| **Input personalisado**             | Um input personalizado, no qual o usuário pode inserir as entradas exigidas pelo programa a ser executado.                                                                                                            |
| **Modo fullscreen**                 | Editor pode ficar fullscreen                                                                                                                                                                                          |
| **Salvar e salvar automaticamente** | Configurações de código são salvas automaticamente após cada 10 segundos para evitar a perda de código ao fechar a janela acidentalmente. O usuário também pode slavar manualmente o código clicando no botão salvar. |
| **Temas**                           | Existem 9 temas de editor disponíveis para escolher.                                                                                                                                                                  |
| **Fontes**                          | 7 fontes diferentes para o editor.                                                                                                                                                                                    |
| **Tamanho da fonte**                | O usuário pode escolher o tamanho da fonte para o editor.                                                                                                                                                             |

## Funções

| Botão              | Função                                                              |
| ------------------ | ------------------------------------------------------------------- |
| **Run**            | Use o botão para compilar o código.                                 |
| **Save**           | Salve manualmente o conteúdo no localStorage.                       |
| **Reset**          | Limpar todo o conteúdo, localStorage e redefinit as configurações.  |
| **Reset Defaults** | Redefinir todas as configurações do editor.                         |
| **UPLOAD**         | Use o botão para escolher o arquivo do sistema local para o upload. |
| **DOWNLOAD**       | Use o botão para fazer download do código no editor em um arquivo.  |
| **Custom Input**   | Use para alternar o input personalizado.                            |

## API

Isso atinge o Coding Blocks Judge API, que você pode encontrar documentado aqui

<https://codingblocks.com/judge-blocks-docs/>

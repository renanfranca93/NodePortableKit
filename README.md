# Node Portable Kit

Este kit permite desenvolver projetos em **Node.js** sem precisar
instalar nada no computador.

## 1. Baixe o kit

Faça o download do arquivo **NodePortableKit.zip** (**[clique aqui para
baixar](./NodePortableKit.zip)**).

## 2. Extraia o arquivo

Após o download, descompacte o arquivo em qualquer pasta do seu
computador.

## 3. Inicie o ambiente

Abra a pasta **NodePortableKit** e execute o arquivo:

``` text
start_terminal.bat
```

Uma janela do terminal será aberta já configurada para utilizar o
**Node.js**, o **npm** e o **SQLite**.

## 4. Crie seus projetos

Todos os projetos da disciplina devem ser criados **dentro da pasta**:

``` text
projects
```

Exemplo:

``` text
NodePortableKit/
├── node/
├── tools/
├── projects/
│   ├── projeto-aula01/
│   ├── projeto-api/
│   └── meu-projeto/
└── start_terminal.bat
```

## 5. Publicando no GitHub

A pasta **NodePortableKit** serve apenas como ambiente de
desenvolvimento e **não deve ser enviada para o GitHub**.

Ao publicar seu código, envie **somente a pasta do projeto** criada
dentro da pasta `projects`.

Exemplo:

**✔ Correto**

``` text
meu-projeto/
```

**✘ Incorreto**

``` text
NodePortableKit/
```

## Versões

-   **Node.js:** v22.23.1
-   **npm:** v10.9.8
-   **SQLite3:** 3.53.3

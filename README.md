# Lógica de Programação

Repositório para a disciplina de Lógica de Programação dos cursos TSI e ECA do IFSul - Campus Charqueadas.

## Motivação

A disciplina de Lógica de Programação tem como objetivo ensinar os conceitos básicos de programação, utilizando a linguagem de programação C. A disciplina é ministrada no primeiro semestre dos cursos Tecnologia em Sistemas para Internet e Engenharia de Controle e Automação.

## Requisitos

Recomendação de softwares para a disciplina de Lógica de Programação. Seguem algumas opções para desenvolvimento de programas em C. Se você não tem certeza de qual utilizar, sugiro o item 1.

## 1. Desenvolvimento local nativo em C.

### Compilador C (Linux)

- GCC

```
sudo apt-get install gcc
sudo apt-get install build-essential gdb
```

### Compilador C (Windows)

- [tdm-gcc (Windows)](http://tdm-gcc.tdragon.net/download)

### Editor de Texto

- [Visual Studio Code](https://code.visualstudio.com/)

### Extensões do Visual Studio Code

- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- [C/C++ Compile Run](https://marketplace.visualstudio.com/items?itemName=danielpinto8zz6.c-cpp-compile-run)

## 2. IDE para desenvolvimento em C (Windows)

- [Code::Blocks](https://www.codeblocks.org/downloads/binaries/)
- [Dev-C++](https://sourceforge.net/projects/orwelldevcpp/)

## 3. Desenvolvimento em container Docker (avançado)

### Dockerfile

```
FROM ubuntu:jammy
RUN apt update -y
RUN apt install -y gcc
RUN apt install -y build-essential gdb
WORKDIR /app
ENTRYPOINT ["tail", "-f", "/dev/null"]
```

### Ambiente de Desenvolvimento

- Se você está escolhendo esta opção, você já deve saber o que está fazendo. Recomendo o VSCode com as extensões citadas no item 1.



# Sistema de Biblioteca

Atividade desenvolvida na matéria de ´´Linguagem de programação 2 (LP2)´´

## Sobre a atividade

A atividade foi desenvolvido para praticar conceitos de Programação Orientada a Objetos (POO) em Java.

O sistema permite cadastrar livros, buscar livros, realizar empréstimos e registrar devoluções.

Os dados ficam armazenados em memória durante a execução do programa, utilizando `ArrayList`.

## Funcionalidades

- **Cadastrar Livro:** cadastra título, autor, ano, ISBN e quantidade.
- **Buscar Livro:** busca um livro pelo título.
- **Empréstimo:** diminui a quantidade disponível.
- **Devolução:** aumenta a quantidade disponível.
- **Teste:** executa alguns exemplos do sistema.
- **Sair:** encerra o programa.

## Estrutura do projeto

```text
SistemaBiblioteca/
│
├── App.java
├── Biblioteca.java
├── Livro.java
├── Usuario.java
├── README.md
└── .gitignore
```

## Classes

### App.java

Classe principal do sistema. Controla o menu e as operações realizadas pelo usuário.

### Biblioteca.java

Representa a biblioteca e controla a quantidade total de livros.

### Livro.java

Representa os livros, armazenando informações como título, autor, ano, ISBN e quantidade disponível.

Também possui as funções de empréstimo, devolução e exibição das informações.

### Usuario.java

Representa o usuário da biblioteca, contendo nome, matrícula e curso.

## Tecnologias

- Java
- Programação Orientada a Objetos
- `ArrayList`
- `Scanner`

## Conceitos de POO

O projeto utiliza:

- Classes e objetos;
- Atributos e métodos;
- Construtores;
- Encapsulamento;
- Sobrecarga de construtores;
- Atributos e métodos `static`.

## Como executar

### Requisito

É necessário ter o Java instalado.

Verifique com:

```bash
java -version
```

### Compilar

Na pasta do projeto, execute:

```bash
javac *.java
```

### Executar

```bash
java App
```

## Menu

```text
1 - Cadastra Livro
2 - Buscar Livro
3 - Emprestimo de Livro
4 - Devolver Livro
5 - Teste
0 - Sair
```

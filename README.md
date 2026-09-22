# Trabalho-de-modelagem-UML2
Sistema de modelagem UML turma 204 informática IEMA IP balsas, Alunos: Erick Milhomem, João Gabriel soares, Samuel Alves Amorim, Thiago da Silv

istema de modelagem UML turma 204 informática IEMA IP balsas, Alunos: Erick Milhomem, João Gabriel soares, Samuel Alves Amorim, Thiago da Silva

README – Sistema de Biblioteca

Sobre o projeto

Este projeto apresenta uma modelagem de um Sistema de Gerenciamento de Biblioteca, desenvolvido com base nos conceitos de Programação Orientada a Objetos (POO) e UML.

O sistema foi pensado para organizar as principais atividades de uma biblioteca, como cadastro de usuários, controle de livros e exemplares, realização de empréstimos, devoluções e gerenciamento de multas.

Objetivo

O principal objetivo do sistema é facilitar o controle das informações e transações realizadas em uma biblioteca.

Entre as principais funções estão:

Cadastro de usuários e funcionários;
Cadastro de livros e autores;
Controle dos exemplares disponíveis;
Registro de empréstimos e devoluções;
Consulta de;
Renovação de;
Controle e pagamento de multas.
Classes do sistema

O sistema é composto por oito classes principais.

Pessoa

É uma classe abstrata que reúne informações comuns entre usuários e funcionários.

Atributos:

eu ia
nome
cpf
e-mail
telefone
Métodos:

obterNome()
PadDados()
Usuário

Representa uma pessoa que utiliza os serviços da biblioteca e realiza empréstimos.

Atributos:

matrícula
dataCadastro
status
Métodos:

podeEmprestar()
consultarEmprestimos()
Funcionário

Representa o funcionário responsável pelo registrador de empréstimos e devoluções.

Atributos:

carga
dataAdmissao
Métodos:

registrarEmprestimo()
registrarDevolucao()
Livro

Representa uma obra cadastrada no acervo da biblioteca.

Atributos:

ISBN
título
editora
anoPublicacao
Métodos:

adicionarAutor()
getExemplaresDisponiveis()
Autor

Representa o autor responsável pela obra.

Atributos:

eu ia
nome
nacionalidade
Método:

obterNome()
Exemplar

Representa uma cópia física de um determinado livro.

Atributos:

código
estadoConservação
nível de disponibilidade
Métodos:

r()
devolver()
Empréstimo

Representa o processo de empréstimo de um exemplar para um usuário.

Atributos:

eu ia
dataEmprestimo
dataPrevistaDevolução
dadosDevolução
status
Métodos:

renovar()
finalizar()
DiasAtraso()
Multa

Representa uma multa gerada quando um empréstimo é devolvido com atraso.

Atributos:

eu ia
valentia
dataGeracao
paga
Métodos:

Valor()
pagar()
Relacionamentos entre as classes

Usuário e Funcionário herdam as características da classe Pessoa.
Um usuário pode realizar vários Empréstimos.
Um Funcionário pode registrar vários Empréstimos.
Um Livro pode possuir um ou mais Autores.
Um Livro pode possuir vários Exemplares.
Um Empréstimo está relacionado a um Exemplar.
Um Empréstimo pode gerar uma Multa quando ocorre atraso.
alcoólatras utilizados

Durante a modelagem foram utilizados conceitos importantes da Programação Orientada a Objetos, como:

Aulas e objetos;
Abstração;
Herança;
Encapsulamento;
Associação;
†
Multiplicidade.
Diagrama de classes

O diagrama representa visualmente a estrutura do sistema e mostra como as classes estão relacionadas entre si. A classe Pessoa serve como base para Usuário e Funcionário, enquanto Livro, Autor, Exemplar, Empréstimo e Multa representam as principais entidades envolvidas no funcionamento da biblioteca.

Integrantes

Projeto: Sistema de Gerenciamento de Biblioteca

Disciplina: Programação Orientada a Objetos / Análise de Sistemas

Finalidade

Este projeto foi desenvolvido para fins acadêmicos, com o objetivo de aplicar na prática os conceitos de modelagem de sistemas e Programação Orientada a Objetos.

# lnpg-cap9-subprogramas-Alisson-Ferro
Repósitorio da matéria LNPG
Aluno: Alisson de Oliveira Ferro
Turma: BSI 2025.1

Tarefa 1 — Modularização em Java
Objetivo: Dividir um programa grande em subprogramas
Foi implementado um sistema que lê 3 notas de alunos, calcula a média, determina a situação do aluno(Aprovado, Reprovado, Recuperação) e gera um relatório final.
Foi criada inicialmente uma versão monolítica e posteriormente uma versão modularizada utilizando subprogramas.
Modularização:
A modularização implementada nesse programa foi utilizada para separar responsabilidades dentro do sistema acadêmico e com isso cada método executa apenas uma tarefa específica, tornando o código mais organizado, reutilizável e fácil de manter. 
Essa abordagem reduz repetição de código e melhora a clareza do fluxo do programa.
Fazendo uma comparação entre as duas versões temos algumas diferenças:

Versão Monolítica: 
Vantagens: Mais simples para programas pequenos, toda lógica fica em um único lugar.
Desvantagens: Código grande e difícil de entender, manutenção mais complicada, baixa reutilização

Versão Modular:
Vantagens: Melhor organização, facilita manutenção e testes, código mais legível 
Desvantagens: Maior quantidade de métodos e exige mais planejamento inicial

Tarefa 2 - Modularização em Python
Identificar responsabilidades independentes e transformá-las em funções.
Implementar um sistema de vendas que lê produtos, quantidade, preço unitário, calcule o subtotal, calcule o desconto, calcule o total final e imprima o cupom formatado
O sistema foi implementado inicialmente de forma monolítica e depois reorganizado em funções.
Modularização: Assim como a primeira tarefa, a modularização melhorou significativamente a legibilidade do programa, com cada função assumindo apenas uma responsabilidade, tornando o fluxo do programa mais compreensivel. 
Permitiu uma reutilização, podendo utilizar as funções em outros programas.

Na versão monolítica, a leitura de dados e os cálculos estavam concentrados em um único bloco de código.
Isso dificultava a reutilização e aumentava a repetição de lógica, principalmente na exibição das informações e nos cálculos financeiros.
Partes que ficaram mais reutilizáveis com a modularização:
calcular_subtotal()
calcular_desconto()
calcular_total()

Tarefa 3 - Passagem de Parâmetros por Valor em Java
Tivemos como objetivo nessa tarefa compreender a passagem por valor de tipos primitivos.
Por que o valor original não mudou?
O valor da variável original não mudou porque Java utiliza passagem por valor para tipos primitivos. 

O que significa “passagem por valor”?
Passagem por valor significa que o método recebe uma cópia do valor armazenado na variável original. O método trabalha apenas com essa cópia local, sem modificar a variável externa

Qual valor realmente foi copiado?
O valor copiado foi: 10. Esse valor foi armazenado na variável x dentro do método.

Tarefa 4 - 
Tivemos como objetivo nessa tarefa o entendimento do comportamento de objetos em chamadas de métodos.
Java possui passagem por referência verdadeira? Não, em Java tudo é passado por valor.

O que exatamente é copiado na chamada? Depende, para tipos primitivos é copiado o próprio valor, para objetos é copiado o endereço de referência do objeto

Por que alterações no objeto permanecem após a chamada? Porque o método e a variável original apontam para o mesmo objeto na memória.

# Sistema de Cadastro de Funcionários

## Descrição

Projeto simples em C++ que simula o cadastro e gerenciamento de diferentes tipos de funcionários: Desenvolvedores, Gerentes e Estagiários. Cada tipo de funcionário tem suas particularidades para cálculo do salário final e exibição de informações.

O sistema permite cadastrar funcionários, mostrar seus dados e calcular o salário final conforme regras específicas.

---

## Funcionalidades

* Cadastro de até 10 funcionários (mínimo 6).
* Funcionários do tipo:

  * Desenvolvedor (salário base + bônus por projeto).
  * Gerente (salário base + bônus mensal).
  * Estagiário (salário base proporcional às horas trabalhadas).
* Exibição das informações detalhadas de cada funcionário.
* Uso de conceitos de orientação a objetos, herança e polimorfismo.

---

## Como usar

1. Compile o projeto com o `make` (requer GNU Make):

```bash
make
```

2. Execute o programa:

```bash
./Sistema_Cadastro_de_Funcionarios.exe
```

3. Siga as instruções do console para cadastrar funcionários, informando:

* Quantidade de funcionários (6 a 10).
* Tipo do funcionário (1 - Desenvolvedor, 2 - Gerente, 3 - Estagiário).
* Nome, ID, salário base, e outras informações específicas (projetos, bônus ou horas trabalhadas).

4. O programa mostrará as informações e salários finais calculados.

---

## Estrutura do Projeto

* `main.cpp`: Função principal e interface do usuário.
* `Funcionarios.hpp` e `Funcionarios.cpp`: Definição das classes `Funcionario`, `Desenvolvedor`, `Gerente` e `Estagiario`, com métodos para manipulação dos dados e cálculos de salário.
* `Makefile`: Script para compilar o projeto facilmente.

---

## Tecnologias e Conceitos

* Linguagem: C++
* Programação Orientada a Objetos (herança, polimorfismo, encapsulamento).
* Conceitos de classes abstratas e métodos virtuais puros.
* Uso de vetores dinâmicos para armazenar objetos de diferentes subclasses.

---

## Autores

* Jhonatan Thiago
* Sávio Moreira 
* Alan Franklin 

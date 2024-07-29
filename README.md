# Projeto de Contas Bancárias em Java

Este projeto é uma simulação de contas bancárias utilizando a linguagem de programação Java. Ele demonstra conceitos de Programação Orientada a Objetos (POO) como herança, encapsulamento e composição.

## Estrutura do Projeto
O projeto é composto pelas seguintes classes:
- ContaCorrente: Classe base que representa uma conta corrente.
- ContaComum: Subclasse de ContaCorrente que representa uma conta comum.
- ContaEspecial: Subclasse de ContaCorrente que representa uma conta especial com limite de crédito.
- Titular: Classe que representa o titular de uma conta. Contém informações pessoais e uma referência para uma ContaCorrente.
- Operacao: Classe com o método main para testar o funcionamento das demais classes.

## Funcionalidades

- Criação de contas comuns e especiais.
- Saque em contas com verificações de saldo e limite.
- Associação de titulares a contas.
- Testes de operações de saque e exibição de informações de titulares.

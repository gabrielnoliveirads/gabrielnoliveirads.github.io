---

title: "Simulador de Fila Bancária"
date: 2026-06-23
excerpt: "Simulação de atendimento bancário com regras de priorização, controle de tempo de espera e desistência automática de clientes, desenvolvida em Python."
github: "https://github.com/gabrielnoliveirads/Fila"
tools:

* Python
* Estruturas de Dados
* Algoritmos

---

# Simulador de Fila Bancária

Desenvolvimento de um sistema para simular o funcionamento de uma fila bancária, aplicando conceitos de Estruturas de Dados e algoritmos de priorização para gerenciar o atendimento de clientes comuns e preferenciais.

O projeto modela o comportamento de uma agência bancária ao longo do tempo, considerando regras de atendimento prioritário, controle de tempo de espera e desistência automática de clientes que permanecem excessivamente na fila.

## Principais Funcionalidades

* Gerenciamento de clientes comuns e preferenciais.
* Controle da ordem de chegada na fila.
* Priorização automática baseada em regras de negócio.
* Monitoramento contínuo do tempo de espera.
* Remoção automática de clientes que ultrapassam o limite de espera.
* Simulação do avanço temporal do sistema.

## Regras de Atendimento

O algoritmo de atendimento segue uma hierarquia de prioridades:

1. Clientes comuns com tempo de espera igual ou superior a 8 unidades de tempo recebem prioridade máxima.
2. Na ausência de clientes nessa condição, o cliente preferencial mais antigo é atendido.
3. Caso não existam clientes preferenciais, o atendimento segue a ordem normal de chegada.

Essa estratégia evita situações de espera indefinida e torna a simulação mais próxima de cenários reais.

## Desafios Técnicos

Durante o desenvolvimento, foram enfrentados desafios relacionados à implementação das regras de priorização e à manipulação dinâmica da fila.

Um dos principais aprendizados foi a necessidade de separar as etapas de decisão do algoritmo para garantir o correto cumprimento das prioridades. Também foi necessário tratar cuidadosamente a remoção de elementos durante a iteração da estrutura de dados, evitando inconsistências causadas pela alteração dos índices da lista.

## Tecnologias Utilizadas

* Python
* Estruturas de Dados
* Algoritmos de Busca e Priorização

## Competências Demonstradas

* Modelagem computacional de problemas reais.
* Manipulação de estruturas de dados lineares.
* Desenvolvimento de algoritmos baseados em regras.
* Simulação de eventos discretos.
* Resolução de problemas e depuração de código.

## Repositório

https://github.com/gabrielnoliveirads/Fila

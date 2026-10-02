# Exercícios de Lógica e Manipulação de Dados em Python (Parte 2)

Este repositório contém a segunda parte do script interativo em Python com foco em estruturas condicionais, laços de repetição e manipulação avançada de listas. O código resolve as questões de 05 a 10, com menus interativos e validação de dados.

## Funcionalidades e Questões

O script aborda os seguintes cenários práticos:

*   **Questão 05 - Funções Matemáticas Nativas:** Calcula soma, média, valor máximo, valor mínimo e quantidade de itens usando funções embutidas do Python (`sum()`, `max()`, `min()`, `len()`).
*   **Questão 06 - Iteração e Filtragem (Ignorando Valores):** Demonstra o uso do comando `continue` para ignorar valores negativos dentro de um laço `for`, somando apenas os valores positivos de uma lista de preços.
*   **Questão 07 - Busca Segura de Elementos:** Verifica a existência de um elemento dentro de uma lista utilizando o operador `in` e localiza sua posição exata com o método `.index()`.
*   **Questão 08 - Sistema Escolar (CRUD e Condicionais):** Um sistema de menu interativo robusto utilizando `while True`. Permite:
    *   Cadastrar alunos e uma quantidade flexível de notas.
    *   Bloquear entradas inválidas (notas negativas ou letras).
    *   Classificar automaticamente o aluno (Aprovado, Recuperação ou Reprovado) em listas separadas baseadas na média final.
    *   Consultar a situação de um aluno específico pelo nome.
*   **Questão 09 - Exclusão Condicional (Gestão de Convidados):** Um loop infinito que remove itens de uma lista com `.remove()` garantindo que o programa não quebre caso o nome não exista, até a lista esvaziar ou o usuário encerrar.
*   **Questão 10 - Sistema de Votação (Contagem e Índices):** Um programa eleitoral que registra votos utilizando `.append()`, contabiliza os resultados finais com `.count()`, e cruza a lista de votos com a lista de candidatos para anunciar o vencedor.

## Requisitos e Módulos

*   **Python 3.x**
*   **Módulos Nativos:** `os` (para limpeza de tela interativa) e `time` (para pausas dramáticas e de leitura).

## Como Executar

1. Salve o código em um arquivo local, como `listas_parte2.py`.
2. Abra o seu terminal.
3. Execute o programa usando o comando:
   ```bash
   python listas_parte2.py

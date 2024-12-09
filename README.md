# Encontrar o Dia da Semana de uma Data

Este programa em Python determina o dia da semana para uma data fornecida. O usuário pode inserir datas nos formatos `dd/mm/aaaa` ou `dd-mm-aaaa`, e o programa irá padronizar e processar a entrada para retornar o dia correspondente.

## Funcionalidades
- Suporte a múltiplos formatos de data (`dd/mm/aaaa` ou `dd-mm-aaaa`).
- Utiliza os módulos `datetime` e `calendar` do Python para cálculos precisos do dia da semana.
- Processamento simples e intuitivo da entrada do usuário.

## Como Funciona
1. O programa utiliza expressões regulares para normalizar o formato da data.
2. Ele analisa a data inserida usando o módulo `datetime` do Python.
3. Determina o dia da semana e retorna o nome do dia usando o módulo `calendar`.

## Como Usar
1. Clone este repositório:
    ```bash
    git clone https://github.com/isaccanedo/day_of_week.git
    cd encontrar-dia-da-semana
    ```
2. Execute o programa:
    ```bash
    python day_of_week.py
    ```
3. Insira uma data no formato `dd/mm/aaaa` ou `dd-mm-aaaa` quando solicitado.

## Exemplo
```bash
Enter date     15-08-2021
Day on 15-08-2021 is Sunday

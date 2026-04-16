# 🛒 ED-Supermercado

Projeto final da unidade curricular de **Estruturas de Dados** — 1º Ano / 2º Semestre  
Engenharia Informática | ESTGV - IPV | 2025/2026

## 📋 Descrição

Sistema de gestão de caixas de atendimento para o supermercado **"Compra Aqui Lda."**  
Desenvolvido em linguagem C, utilizando estruturas de dados como filas, listas ligadas e hashing.

## 🏗️ Arquitetura
ED-Supermercado/
├── main.c          # Ponto de entrada e menus
├── caixa.c/h       # Gestão das caixas de atendimento
├── cliente.c/h     # Gestão dos clientes
├── produto.c/h     # Gestão dos produtos
├── fila.c/h        # Estrutura de fila (queue)
└── utils.c/h       # Funções auxiliares

## ⚙️ Funcionalidades

- Carregar dados a partir de ficheiros
- Abrir/fechar caixas automaticamente com base em `MAX_FILA` e `MIN_FILA`
- Transferir clientes entre caixas
- Pesquisar clientes na fila
- Política de compensação por tempo de espera excessivo
- Histórico em `.csv`
- Estatísticas de desempenho no final da simulação

## 🛠️ Compilação

```bash
gcc -o supermercado main.c caixa.c cliente.c produto.c fila.c utils.c -o programa.exe
```

## 👤 Autor

[Rodrigo Couto](https://github.com/DevCoutoo)

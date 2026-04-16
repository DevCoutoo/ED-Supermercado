# 🛒 ED-Supermercado

Projeto final da unidade curricular de **Estruturas de Dados** — 1º Ano / 2º Semestre  
Engenharia Informática | ESTGV - IPV | 2025/2026

## 📋 Descrição

Sistema de gestão de caixas de atendimento para o supermercado **"Compra Aqui Lda."**  
Desenvolvido em linguagem C, utilizando estruturas de dados como filas, listas ligadas e hashing.

## 🏗️ Arquitetura
ED-Supermercado/
├── src/
│   ├── main.c
│   ├── caixa.c / caixa.h        # struct Caixa, abrir/fechar
│   ├── cliente.c / cliente.h    # struct Cliente, produtos
│   ├── fila.c / fila.h          # fila de clientes (queue)
│   ├── lista.c / lista.h        # lista de caixas
│   ├── hash.c / hash.h          # pesquisa rápida de clientes
│   ├── simulacao.c / simulacao.h # lógica principal (MAX_FILA, MIN_FILA, etc.)
│   ├── ficheiros.c / ficheiros.h # leitura Dados.txt, Configuracao.txt
│   └── relatorio.c / relatorio.h # gravação CSV, stats finais
├── data/
│   ├── Configuracao.txt
│   └── Dados.txt
├── output/                       # ficheiros gerados (CSV, historico)
└── README.md / docs (doxygen)

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
gcc src/*.c -o supermercado.exe
```

## 👤 Autor

[Rodrigo Couto](https://github.com/DevCoutoo)

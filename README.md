# LightWeek - Gerenciamento de Sessões de Recarga

Projeto desenvolvido para a **Sprint 3 de Data Structures and Algorithms**, com o objetivo de transformar o simulador de recarga em um sistema que armazena, pesquisa, ordena e analisa várias sessões.

## Equipe

| Integrante | RM |
| --- | --- |
| Maykon de Lima Silva | 574022 |
| Felipe Pereira Restivo | 570712 |
| Gabriel Rodrigues Zappelloni | 572060 |
| Rodger Costa Rios | 571438 |
| Kenichi Caio Yamamoto | 569815 |

**Turma:** 1CCPK

## Funcionalidades

- Cadastro de várias sessões em uma lista;
- Representação de cada sessão com a classe `Sessao`;
- Validação de ID duplicado, números negativos, textos vazios e opções inválidas;
- Listagem das sessões em formato de tabela;
- Busca sequencial implementada manualmente;
- Ordenação manual com Insertion Sort;
- Ordenação por ID, energia, custo ou tempo;
- Estatísticas calculadas a partir das sessões cadastradas;
- Menu contínuo até o usuário escolher encerrar.

## Como executar

É necessário ter o Python 3 instalado.

No terminal, dentro da pasta do projeto, execute:

```bash
python sistema_recarga.py
```

No Windows também pode ser necessário utilizar:

```bash
py sistema_recarga.py
```

O programa não utiliza bibliotecas externas.

## Menu principal

```text
=====================================
     ESTAÇÃO DE RECARGA LIGHTWEEK
=====================================
1 - Nova sessão de recarga
2 - Listar sessões
3 - Buscar sessão
4 - Ordenar sessões
5 - Estatísticas
6 - Encerrar
```

## Estrutura do projeto

```text
lightweek-sprint3-DSA/
├── sistema_recarga.py
├── README.md
├── DOCUMENTACAO.md
└── tests/
    └── test_sistema_recarga.py
```

## Documentação

A explicação da classe, do funcionamento, dos algoritmos e da análise Big-O está no arquivo [`DOCUMENTACAO.md`](DOCUMENTACAO.md).



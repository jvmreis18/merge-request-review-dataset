# Pacote de Replicação

Este repositório contém o conjunto de dados anonimizado utilizado na avaliação empírica apresentada no artigo submetido ao **SAST**.

Os dados correspondem ao histórico de *Merge Requests* e do processo de revisão de código de um projeto real de desenvolvimento de software, coletados ao longo de um período contínuo de 12 meses. Para preservar o processo de avaliação duplo-cego (*double-blind review*), todas as informações que poderiam identificar autores, instituições, organizações, repositórios, projetos ou desenvolvedores foram removidas ou anonimizadas.

## Estrutura do Repositório

```
.
├── comentarios_anon.csv
├── discussoes_anon.csv
├── merge_requests_anon.csv
├── estatisticas_gerais_anon.csv
└── README.md
```

## Descrição dos Arquivos

| Arquivo | Descrição |
|---------|-----------|
| `merge_requests_anon.csv` | Informações gerais dos *Merge Requests* analisados durante o estudo. |
| `comentarios_anon.csv` | Comentários realizados durante o processo de revisão de código. |
| `discussoes_anon.csv` | Discussões associadas aos *Merge Requests*. |
| `estatisticas_gerais_anon.csv` | Estatísticas agregadas utilizadas na avaliação quantitativa. |

## Descrição do Conjunto de Dados

O conjunto de dados reúne informações extraídas do histórico de revisão de código de um projeto real, permitindo analisar aspectos relacionados ao processo de desenvolvimento e revisão de testes automatizados.

A base contempla informações como:

- histórico de *Merge Requests*;
- participantes envolvidos nas revisões;
- comentários e discussões realizadas durante o *Code Review*;
- métricas agregadas utilizadas na avaliação experimental.

Todos os identificadores pessoais foram substituídos por identificadores anônimos, preservando a consistência das interações entre autores, revisores, comentários e *Merge Requests*.

## Resumo dos Dados

| Métrica | Valor |
|---------|------:|
| *Merge Requests* integrados | 97 |
| Casos de teste Web | 115 |
| Casos de teste de API | 185 |
| Linhas de código modificadas | 53.520 |
| Comentários em revisões | 1.613 |
| Média de participantes por *Merge Request* | 2,13 |
| Tempo médio para integração | 4,0 dias |

## Processo de Anonimização

Os dados foram anonimizados antes de sua disponibilização, incluindo a remoção ou substituição de:

- nomes de desenvolvedores e revisores;
- nomes de usuários (*usernames*);
- instituições e organizações;
- nomes de projetos e repositórios;
- referências identificáveis presentes em comentários e discussões.

A anonimização preserva a estrutura e as relações existentes entre os registros, permitindo a reprodução das análises apresentadas no artigo sem comprometer a confidencialidade das informações originais.

## Reprodutibilidade

Os conjuntos de dados disponibilizados neste repositório correspondem aos dados utilizados na avaliação experimental apresentada no artigo, permitindo a reprodução das análises quantitativas e qualitativas descritas no estudo.

## Licença

Este conjunto de dados é disponibilizado sob a licença **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

A reutilização, distribuição e adaptação dos dados são permitidas, desde que a fonte seja devidamente citada.

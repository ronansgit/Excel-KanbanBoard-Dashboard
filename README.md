# Dashboard Kanban Board — Excel

Dashboard interativo desenvolvido no Microsoft Excel para acompanhamento e análise de tarefas em uma estrutura visual inspirada em **Kanban Boards**.

---

## 1. Preview

![Dashboard Kanban Board](dashboard.png)

---

## 2. Overview

Projeto desenvolvido para demonstrar a aplicação de recursos avançados do Excel na construção de uma solução de análise e acompanhamento de tarefas.

O dashboard integra **Power Query, Power Pivot e DAX** em um fluxo de tratamento, modelagem e visualização de dados.

A interface foi planejada com princípios de **UI/UX**, priorizando hierarquia visual, usabilidade e leitura rápida dos principais indicadores.

O usuário pode utilizar filtros interativos para explorar as informações por diferentes dimensões.

---

## 3. Dados > Dashboard

O projeto utiliza o **Power Query** como etapa de preparação dos dados antes da construção do modelo analítico.

### Fluxo de Dados

```text
Base de Dados
      │
      ▼
Power Query
      │
      ├── Tratamento
      ├── Padronização
      └── Transformação
      │
      ▼
Modelo de Dados
      │
      ▼
Tabelas Dinâmicas
      │
      ▼
Dashboard
```

### Base de Dados

A consulta principal foi estruturada no Power Query para organizar e preparar os dados utilizados pelo dashboard.

Essa etapa permite centralizar o tratamento dos dados e manter uma estrutura consistente para as análises posteriores.

![Base de Dados](base-dados.png)

---

## 4. Tabela dCalendário

Foi criada uma dimensão de calendário diretamente no **Power Query** para estruturar as análises relacionadas a datas.

A `dCalendário` contém informações utilizadas na segmentação e análise temporal dos dados, como:

* Data
* Ano
* Mês
* Número do mês
* Trimestre
* Dia
* Dia da semana

A utilização de uma dimensão de calendário também permite estruturar corretamente os relacionamentos do modelo e as análises baseadas em períodos.

![Criação da tabela dCalendário](dcalendario.png)

---

## 5. Tabelas Dinâmicas

As **Tabelas Dinâmicas** funcionam como uma camada de análise entre o modelo de dados e a interface final do dashboard.

Elas foram utilizadas para estruturar os dados necessários aos principais componentes visuais, permitindo analisar diferentes aspectos das tarefas.

Entre as informações utilizadas estão:

* Status das tarefas
* Prioridades
* Responsáveis
* Prazos
* Quantidade de atividades
* Distribuição das tarefas

![Tabelas Dinâmicas](tabelas-dinamicas.png)

---

## 6. Esboço do Dashboard

Antes da construção da interface final, foi desenvolvido um esboço para definir a estrutura visual e a distribuição dos componentes.

O planejamento considerou:

* Hierarquia das informações
* Posicionamento dos indicadores
* Organização dos filtros
* Área destinada ao Kanban
* Fluxo de leitura
* Usabilidade da interface

Essa etapa serviu como referência para a implementação do layout final.

![Esboço do Dashboard](esboco-dashboard.png)

---

## 7. Ferramentas e Skills

| Tecnologia / Skill       | Aplicação                                           |
| ------------------------ | --------------------------------------------------- |
| **Microsoft Excel**      | Desenvolvimento da solução e interface do dashboard |
| **Power Query**          | ETL, tratamento e transformação dos dados           |
| **Power Pivot**          | Modelagem e relacionamento entre tabelas            |
| **DAX**                  | Criação de medidas e cálculos analíticos            |
| **Segmentação de Dados** | Filtros e interação com o dashboard                 |
| **UI/UX Design**         | Estrutura visual, hierarquia e usabilidade          |

---

## 8. Estrutura do Projeto

```text
Dashboard-Kanban-Board/
│
├── Dashboard Kanban Board.xlsx
│
├── Dark.PNG
├── Base_Dashboard.PNG
├── Criação da tabela dCalendário.PNG
├── Tabelas Dinâmicas.PNG
├── Esboço.PNG
│
└── README.md
```

---

## 9. Conceitos Aplicados

O projeto demonstra a integração de diferentes recursos do Excel em uma única solução:

**ETL**
→ preparação e transformação dos dados com Power Query.

**Modelagem**
→ estruturação das tabelas e relacionamentos utilizando Power Pivot.

**Análise**
→ criação de medidas e indicadores com DAX.

**Visualização**
→ construção de um dashboard interativo com Tabelas Dinâmicas e Segmentações de Dados.

**UI/UX**
→ planejamento e organização da interface para facilitar a interpretação das informações.

---

## 10. Resultado

O resultado é uma solução de análise construída inteiramente no Excel, combinando **tratamento de dados, modelagem, análise, interatividade e design de interface** em um único projeto.

O projeto faz parte do meu portfólio de soluções desenvolvidas com Excel e ferramentas de análise de dados.

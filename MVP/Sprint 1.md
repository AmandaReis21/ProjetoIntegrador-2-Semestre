# Sprint 1 - Backlog

## Registro da Sprint

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|------------|------------|--------|
| 1 | Alta | Como Analista de Dados, desejo coletar, limpar e estruturar os dados de mortalidade, severidade dos sinistros e população (2015-2025), visando criar uma base confiável para análises e painéis. | 4 horas | 1 |
| 2 | Alta | Como Analista de Dados, desejo tratar, padronizar e integrar os dados coletados das bases **DATASUS, IBGE e PRF**, organizando informações de mortalidade, população, localização e sinistros de trânsito, para gerar uma base de dados consolidada, confiável e preparada para as análises no Power BI. | 4 horas | 1 |
| 3 | Alta | Como Analista de Dados, desejo categorizar a severidade dos sinistros em Grave (sem fatalidade/capotamento/choque/colisão), Gravíssimo (atropelamento sem fatalidade) e Fatal, para refletir com precisão o grau de risco das ocorrências. | 2 horas | 1 |
| 4 | Média | Como Pesquisador de Segurança Viária, desejo analisar a relação entre a taxa de mortalidade e a população, para compreender o impacto real dos sinistros considerando a densidade demográfica. | 3 horas | 1 |
| 5 | Média | Como Gestor do Observatório, desejo visualizar a comparação dos dados de sinistros entre os âmbitos nacional e regional, visando identificar regiões críticas que exigem intervenções. | 3 horas | 1 |
| 6 | Baixa | Como Gestor do Observatório, desejo acessar uma versão inicial do Power BI com as métricas levantadas, para alinhar as expectativas sobre o andamento e o layout preliminar. | 2 horas | 1 |

## Relatório da Sprint I

[Acesse aqui](https://docs.google.com/document/d/1qeIFFxbTSp26ceC6APSclErt9Av62AAGU-kcCncGHkc/edit?usp=sharing)

## Apresentação Sprint I

[Acesse aqui](https://github.com/user-attachments/files/31840310/Meridian.Log.-.Apresentacao.Inicial.pdf)

# 📌 MVP - [Níveis dos Sinistros e Relação entre Métricas]

## 🎯 Objetivo do MVP

> Descrever de forma clara qual é o propósito do MVP:

- **Qual problema resolve?**

> Dificuldade em visualizar e relacionar os dados de sinistros de trânsito, seus níveis de gravidade, mortalidade e características populacionais, dificultando a identificação de padrões e diferenças entre regiões.

- **Qual hipótese será validada?**

> A hipótese de que a análise conjunta dos níveis de gravidade dos sinistros, da mortalidade e da população permite identificar padrões e diferenças relevantes entre períodos e regiões.

- **Qual valor será entregue ao usuário final?**

> Disponibilizar uma visualização clara e interativa dos indicadores de sinistros, permitindo comparar níveis de gravidade, mortalidade e população entre diferentes regiões e períodos.

---

## 📝 Descrição da Solução

> Breve explicação do que será desenvolvido e entregue nesta etapa:

- **Funcionalidades principais incluídas:**

> - Visualização dos níveis de gravidade dos sinistros.
> - Tratamento, padronização e integração dos dados das bases **DATASUS, IBGE e PRF**.
> - Consolidação das informações de mortalidade, população, localização e sinistros de trânsito.
> - Análise da relação entre mortalidade e população.
> - Comparação dos indicadores entre diferentes regiões.
> - Comparação dos dados ao longo do período de 2015 a 2025.
> - Segmentação dos sinistros em Grave, Gravíssimo e Fatal.
> - Visualização inicial dos indicadores no Power BI.

- **Limitações conhecidas:**

> - Análise limitada aos dados disponíveis para o período de 2015 a 2025.
> - Os resultados dependem da qualidade e disponibilidade das bases de dados utilizadas.
> - Nesta etapa, a análise está concentrada nas métricas de mortalidade, severidade e população.
> - A integração dos dados depende da compatibilidade entre os campos e períodos disponíveis nas bases DATASUS, IBGE e PRF.
> - A análise de localização e infraestrutura relacionada aos pontos de parada será aprofundada nas próximas sprints.

- **Escopo reduzido: (somente o essencial para validar a ideia)**

> - Dashboard inicial no Power BI.
> - Dados de 2015 a 2025.
> - Dados provenientes das bases DATASUS, IBGE e PRF.
> - Tratamento, padronização e integração das bases utilizadas.
> - Indicadores de mortalidade, severidade dos sinistros e população.
> - Relação entre mortalidade e população.
> - Comparação nacional e regional.
> - Classificação dos sinistros em Grave, Gravíssimo e Fatal.

---

## 👥 Personas / Usuários-Alvo

- **Gestor do Observatório:** responsável por definir as expectativas, requisitos e objetivos do projeto, além de acompanhar e avaliar os resultados obtidos.

- **Analista de Dados:** responsável pelo tratamento, organização, segregação, padronização, integração e limpeza dos dados, garantindo sua qualidade e adequação para análise.

- **Pesquisador de Segurança Viária:** responsável por reunir, interpretar e analisar os dados relacionados à segurança viária, buscando compreender os principais indicadores e padrões identificados.

---

## 🚀 Próximos Passos

- Levantar pontos de parada e analisar sua distância em relação aos sinistros com veículos pesados.
- Criar páginas no Power BI para organizar e detalhar as relações entre as métricas.
- Categorizar movimentações por Unidade da Receita Federal e modais de transporte, identificando as principais frotas por região.
- Aprofundar a análise espacial dos sinistros e dos pontos de parada nas próximas sprints.
- Preparar a integração das novas informações ao modelo de dados utilizado no Power BI.

---

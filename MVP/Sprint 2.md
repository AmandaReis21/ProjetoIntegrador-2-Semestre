# Sprint 2 - Backlog

## Registro da Sprint

| Rank | Prioridade | User Story | Estimativa | Sprint |
|------|------------|------------|------------|--------|
| 7 | Média | Como Pesquisador de Segurança Viária, desejo categorizar a movimentação por Unidade da Receita Federal e modais de transporte, para identificar o perfil e volume das principais frotas por região. | 4 horas | 2 |
| 8 | Baixa | Como Gestor do Observatório, espero que o Power BI seja organizado em páginas separadas por tipos de relações entre as métricas, para proporcionar uma visualização mais limpa e detalhada das informações. | 2 horas | 2 |
| 9 | Média | Como Analista de Dados, desejo uma análise comparativa proporcional ao ano de 2020, dado que devido à pandemia teve seus dados afetados, para a comparação verídica de quantidade de acidentes em relação às métricas. | 4 horas | 2 |

## Relatório da Sprint II

[Acesse aqui](https://docs.google.com/document/d/1LRmfz6N4rVNsMZTuEqgW9m98wc8ByKUY_4ah44g85ek/edit?usp=sharing)

## Apresentação Sprint II

[Acesse aqui](https://canva.link/4bu1bq7j2ktzy9z)

# 📌 MVP - [Análise Comparativa Proporcional entre os Anos e Relação entre Métricas]

## 🎯 Objetivo do MVP

Descrever de forma clara qual é o propósito do MVP:

- **Qual problema resolve?**

> A dificuldade em visualizar e relacionar os dados de sinistros de trânsito, seus níveis de gravidade, mortalidade e características populacionais dificulta a identificação de padrões e diferenças entre regiões. Além disso, fatores que afetam determinados períodos, como a pandemia em 2020, podem comprometer a comparação entre os anos. A análise da localização dos pontos de parada e das características das frotas também pode contribuir para uma compreensão mais ampla dos fatores relacionados aos sinistros com veículos pesados.

- **Qual hipótese será validada?**

> A hipótese de que a análise conjunta dos níveis de gravidade dos sinistros, da mortalidade, da população, das características das frotas e da localização dos pontos de parada permite identificar padrões e diferenças relevantes entre períodos e regiões. Também se busca verificar se o tratamento das particularidades dos dados de 2020 possibilita comparações mais consistentes entre os anos analisados.

- **Qual valor será entregue ao usuário final?**

> Disponibilizar uma visualização clara e interativa dos indicadores de sinistros, permitindo comparar níveis de gravidade, mortalidade e população entre diferentes regiões e períodos. A solução também busca ampliar a análise das ocorrências envolvendo veículos pesados, facilitar a identificação de padrões nas movimentações por região e oferecer informações que auxiliem na compreensão dos fatores associados à segurança viária.

---

## 📝 Descrição da Solução

Breve explicação do que será desenvolvido e entregue nesta etapa:

- **Funcionalidades principais incluídas:**

> - Tratamento, padronização e integração dos dados das bases DATASUS, IBGE e PRF.
> - Visualização dos níveis de gravidade dos sinistros.
> - Análise da relação entre mortalidade e população.
> - Comparação dos indicadores entre diferentes regiões.
> - Comparação dos dados ao longo do período de 2015 a 2025.
> - Organização do Power BI em páginas separadas por relações entre as métricas, facilitando a leitura e a interpretação dos resultados.
> - Levantamento da localização dos pontos de parada de descanso e cálculo das distâncias até os sinistros envolvendo veículos pesados.
> - Categorização das movimentações por Unidade da Receita Federal e modais de transporte, permitindo identificar o perfil e o volume das principais frotas por região.
> - Análise comparativa dos dados de 2020, considerando o impacto da pandemia e buscando tornar as comparações entre os anos mais consistentes.

- **Limitações conhecidas:**

> - Análise limitada aos dados disponíveis para o período de 2015 a 2025.
> - Os resultados dependem da qualidade, disponibilidade e compatibilidade das bases de dados utilizadas.
> - A análise do impacto da pandemia depende dos dados disponíveis e dos critérios adotados para realizar as comparações.
> - A identificação de possíveis relações entre os pontos de parada e os sinistros não comprova, isoladamente, uma relação de causa e efeito.
> - As análises dependem da disponibilidade de informações geográficas suficientes para relacionar os pontos de parada à localização dos sinistros.
> - A previsão estatística de futuros acidentes e o mapeamento de rotas mais viáveis permanecem como atividades previstas para a Sprint 3.

- **Escopo reduzido: (somente o essencial para validar a ideia)**

> - Continuidade do dashboard no Power BI a partir da estrutura inicial desenvolvida na Sprint 1.
> - Utilização dos dados de 2015 a 2025.
> - Indicadores de mortalidade, severidade dos sinistros e população.
> - Relação entre mortalidade e população.
> - Comparação nacional e regional.
> - Organização das páginas do Power BI por relações entre métricas.
> - Levantamento dos pontos de parada e análise de suas distâncias em relação aos sinistros com veículos pesados.
> - Categorização das movimentações por Unidade da Receita Federal e modais de transporte.
> - Análise comparativa proporcional dos dados de 2020, considerando o impacto da pandemia.

---

## 👥 Personas / Usuários-Alvo

- **Gestor do Observatório:** responsável por definir as expectativas, requisitos e objetivos do projeto, além de acompanhar e avaliar os resultados obtidos.

- **Analista de Dados:** responsável pelo tratamento, organização, segregação, padronização, integração e limpeza dos dados, garantindo sua qualidade e adequação para análise.

- **Pesquisador de Segurança Viária:** responsável por reunir, interpretar e analisar os dados relacionados à segurança viária, buscando compreender os principais indicadores, características das frotas e padrões identificados nos sinistros.

---

## 🚀 Próximos Passos

- Mapear os pontos de parada de descanso e analisar suas distâncias em relação à localização dos sinistros envolvendo veículos pesados.
- Integrar as informações de localização dos pontos de parada às análises espaciais no Power BI.
- Desenvolver um modelo de previsão estatística de futuros acidentes.
- Analisar e mapear rotas mais viáveis, buscando contribuir para a proposição de ações preventivas.
- Finalizar e validar o Power BI com as análises e previsões integradas.
- Revisar os resultados obtidos e preparar a apresentação final das informações aos stakeholders.

---

## 📂 Anexos / Evidências

- **5W2H:** [API - 5W2H](https://1drv.ms/x/c/4ca35ab9cf750f06/IQCqwWvYchPWTajafKZr6_ybAcMVYJb9fMHc1wML4qKDKkY?e=1DFaSg)

- **Relatório da Sprint I:** [Acesse aqui](https://docs.google.com/document/d/1qeIFFxbTSp26ceC6APSclErt9Av62AAGU-kcCncGHkc/edit?usp=sharing)

- **Apresentação inicial:** [Acesse aqui](https://github.com/user-attachments/files/31840310/Meridian.Log.-.Apresentacao.Inicial.pdf)

- **Ferramentas utilizadas:** Power BI, Google Colab e Excel.

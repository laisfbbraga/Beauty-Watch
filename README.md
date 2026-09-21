# BeautyWatch | Vigilante da Beleza
**Verifique se o cosmético que você usa é aprovado e regularizado pela ANVISA**


### O que é o BeautyWatch?
O Vigilante da Beleza é um pipeline de dados que processa os dados abertos oficiais da ANVISA para ajudar consumidores brasileiros a verificar se os cosméticos que usam estão devidamente registrados e aprovados para comercialização no Brasil. Por meio de um dashboard público no Streamlit, qualquer pessoa pode buscar um produto ou marca e ver instantaneamente seu status regulatório, validade do registro e informações de segurança, em linguagem simples, sem precisar navegar pelo portal técnico da ANVISA.

---
### Por que o BeautyWatch?

Feature |Portal ANVISA | BeautyWatch|
|---|---|---|
|Busca amigável para consumidoras |❌| ✅|
|Status em linguagem simples |	❌| ✅|
|Alerta de registro próximo ao vencimento|✅| ✅|
|Explicação com IA em linguagem acessível|❌| ✅|
|Interface mobile-friendly|❌|✅|

**Uma busca. Saiba o que você está colocando na sua pele.**

---

### O problema que resolve 
O Brasil é o 4º maior mercado de cosméticos do mundo — mas a maioria das consumidoras nunca verificou se o produto que usa tem registro válido na ANVISA.

Cosméticos sem registro não passaram pelas avaliações de segurança exigidas por lei e podem conter substâncias proibidas ou ingredientes não avaliados. O Vigilante da Beleza traduz isso em uma busca simples: você digita o produto e sabe na hora se é seguro e aprovado para ser vendido no Brasil.

Este projeto é também a minha jornada prática em engenharia de dados, onde cada funcionalidade representa uma habilidade técnica real.

---
### Fonte de dados
Todos os dados vêm do portal de dados abertos oficial da ANVISA — disponíveis publicamente, sem restrições de uso, atualizados regularmente pelo órgão regulador federal de saúde do Brasil.

- dados.anvisa.gov.br

---

### Tech Stack
Camada |	Tecnologia | Status |
|---|---|---|
|Fonte de dados | ANVISA - dados abertos | ✅ Em uso|
|Análise exploratória |	Python · Pandas	| ✅ Em uso|
|Coleta automatizada | Python · Requests (API ANVISA) | 🔜 Planejado|
|Armazenamento | Google BigQuery · Cloud Storage | 🔜 Planejado|
|Transformação | dbt |🔜 Planejado|
|Orquestração |	Apache Airflow	| 🔜 Planejado|
|Cloud | Gemini API  |	🔜 Planejado|
|Frontend |	Streamlit | 🔜 Planejado|
|Version Control | Git · GitHub | ✅ Em uso|

---

### Arquitetura

*(Planejado — diagrama em breve)*

---

### Como Executar

*(Planejado — instruções serão adicionadas conforme o projeto for construído)*

---

### Status do Projeto

🚧 *Em desenvolvimento ativo — construído como parte de uma jornada de aprendizado em engenharia de dados.*

---
### Fases:

- [ ] Fase 0 — Git + GitHub e estrutura do repositório
- [ ] Fase 1 — Python + Requests (API da ANVISA)
- [ ] Fase 2 — Análise exploratória do dataset ANVISA (Python + Pandas)
- [ ] Fase 3 — Análise SQL no BigQuery
- [ ] Fase 4 — Pipelines (Airflow + dbt)
- [ ] Fase 5 — Deploy na nuvem (GCP)
- [ ] Fase 6 — Explicações com IA em linguagem simples (Gemini)
- [ ] Fase 7 — Dashboard público (Streamlit)



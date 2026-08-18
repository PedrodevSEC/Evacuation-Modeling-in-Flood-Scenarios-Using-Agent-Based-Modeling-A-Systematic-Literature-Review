# Artefatos da Revisão Sistemática da Literatura

Este repositório disponibiliza os artefatos utilizados na execução da
Revisão Sistemática da Literatura (RSL) apresentada no artigo
"Evacuation-Modeling-in-Flood-Scenarios-Using-Agent-Based-Modeling-A-Systematic-Literature-Review".

O objetivo deste repositório é fornecer transparência ao processo de
seleção e classificação dos estudos, permitindo acompanhar as decisões
tomadas ao longo das diferentes etapas da revisão.

## Estrutura do repositório

Os artefatos estão organizados em três planilhas, correspondentes às
principais etapas do processo de seleção e análise dos estudos:

- `Camada_1.xlsx` — primeira etapa de triagem dos estudos recuperados;
- `Camada_2.xlsx` — classificação dos estudos segundo as características
  analisadas na revisão;
- `Camada_3.xlsx` — etapa de análise detalhada e seleção dos estudos
  considerados para a análise final.

## Processo da revisão

A revisão foi conduzida a partir de buscas realizadas nas bases
[Scopus] e [IEEE Xplore], utilizando as strings de busca apresentadas
no artigo.

O processo de seleção foi organizado em três camadas.

### Camada 1 — Triagem inicial

Na primeira camada, os estudos recuperados foram analisados a partir
do título, resumo e informações disponíveis no registro bibliográfico.

Os estudos foram classificados em três categorias:

- **Incluir** — estudos considerados aderentes ao escopo da revisão;
- **Talvez** — estudos potencialmente relevantes, mantidos como segunda
  prioridade durante a triagem;
- **Excluir** — estudos que não atendiam aos critérios estabelecidos.

Os motivos de exclusão e as respectivas classificações foram
padronizados por meio de códigos, conforme apresentado no artigo.

### Camada 2 — Classificação dos estudos

Os estudos selecionados na primeira camada foram classificados segundo
diferentes características de interesse da revisão, incluindo:

- tipo de cenário de crise;
- escala da simulação;
- representação do comportamento cognitivo;
- ferramenta ou plataforma utilizada;
- disponibilidade das informações.

Essas classificações permitiram caracterizar o conjunto de estudos e
realizar os recortes utilizados nas etapas posteriores.

### Camada 3 — Análise detalhada

Na terceira camada, os estudos selecionados a partir dos critérios
anteriores foram submetidos à análise detalhada.

Nessa etapa foram registradas as decisões finais de inclusão e exclusão,
bem como os respectivos motivos quando aplicável.

O conjunto resultante dessa etapa corresponde aos estudos utilizados
na análise final apresentada no artigo.

## Relação entre os artefatos e o artigo

As três planilhas permitem acompanhar o caminho percorrido desde a
triagem inicial até a seleção final dos estudos:

```text
Busca bibliográfica
        ↓
Camada 1 — Triagem inicial
        ↓
Camada 2 — Classificação
        ↓
Camada 3 — Análise detalhada
        ↓
Estudos incluídos na análise final
```

## Como reproduzir a seleção dos estudos

As planilhas permitem reproduzir o processo de seleção dos estudos a
partir das três etapas de análise. Para obter os mesmos resultados
apresentados no artigo, devem ser aplicados os filtros descritos a seguir.

### 1. Camada 1 — Triagem inicial

Na planilha `Camada_1.xlsx`, utilize o filtro disponível na coluna
correspondente à decisão de classificação.

Selecione apenas os registros identificados pelo ícone **✅**.

A aplicação desse filtro resulta em **273 estudos**, que correspondem
aos trabalhos selecionados para a segunda etapa da revisão.

Os estudos classificados nas demais categorias não são considerados
nas etapas seguintes.

### 2. Camada 2 — Classificação e refinamento

Na planilha `Camada_2.xlsx`, devem ser aplicados simultaneamente os
seguintes filtros:

- **Tipo de crise:** Enchente;
- **Escala:** Regional;
- **Comportamento humano:** Sim;
- **Ferramenta:** todas as opções, exceto **Não informado**;
- **Disponibilidade:** Sim.

A aplicação conjunta desses critérios resulta em **18 estudos**,
selecionados para a análise detalhada da terceira camada.

### 3. Camada 3 — Seleção final

Na planilha `Camada_3.xlsx`, utilize o filtro da coluna de decisão final.

Selecione apenas os estudos em que:

- **Incluir = Sim**.

Esse filtro resulta em **7 estudos**, que correspondem ao conjunto final
de trabalhos incluídos na análise apresentada no artigo.

### Resumo do processo

O processo de seleção pode ser reproduzido da seguinte forma:

```text
Camada 1
Filtro: ✅
        ↓
273 estudos

Camada 2
Tipo de crise = Enchente
Escala = Regional
Comportamento humano = Sim
Ferramenta ≠ Não informado
Disponibilidade = Sim
        ↓
18 estudos

Camada 3
Incluir = Sim
        ↓
7 estudos finais

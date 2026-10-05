# Métricas Individuais no Desenvolvimento de Software

> **Grupo 4 · Tema 5 — Desenvolvimento, Métricas e IA no Ecossistema de Software e de TI**

## Integrantes

- **William Libardoni**
- **Bianca Scarton**
- **Júlio César Pegoraro Souza**

## Pergunta central

**É possível medir quanto cada desenvolvedor produz e criar um ranking?**

## Posicionamento do grupo

> **Medir, sim. Ranquear, não de forma confiável com uma métrica isolada.**

Métricas individuais podem fornecer sinais úteis sobre o trabalho de um desenvolvedor, mas produtividade em software envolve resultado, atividade, colaboração, experiência, fluxo e contexto. Transformar um desses sinais em uma nota única pode esconder partes importantes do trabalho e criar incentivos para otimizar o indicador em vez do resultado.

Nossa proposta é tratar métricas como instrumentos de diagnóstico:

**Métrica → sinal → investigação → contexto → decisão**

e não como:

**Métrica → score → ranking → julgamento**

---

## Conteúdo

| Capítulo | Questão |
|---|---|
| [1. O problema](conteudo/01-problema.md) | O que realmente significa medir produtividade? |
| [2. SPACE](conteudo/02-space.md) | Por que produtividade é multidimensional? |
| [3. Métricas individuais](conteudo/03-metricas-individuais.md) | O que commits, LOC e PRs conseguem — e não conseguem — mostrar? |
| [4. DevEx](conteudo/04-devex.md) | Como ambiente, feedback, carga cognitiva e fluxo afetam produtividade? |
| [5. IA e produtividade](conteudo/05-ia-e-produtividade.md) | IA torna métricas tradicionais ainda mais frágeis? |
| [6. Conclusão](conteudo/06-conclusao.md) | Como propomos medir sem reduzir pessoas a um placar? |
| [Referências](referencias/referencias.md) | Artigo-âncora e fontes complementares |

## Ideia central

Desenvolvimento de software é trabalho intelectual e colaborativo. Uma pessoa pode escrever pouco código e gerar grande impacto ao eliminar complexidade, revisar uma mudança crítica, prevenir um incidente, orientar colegas ou tomar uma decisão arquitetural.

Por isso, **atividade não é sinônimo de produtividade e produtividade não é sinônimo de impacto**.

### Exemplo hipotético

**Desenvolvedor A**
- 47 commits
- 12 pull requests
- 3.200 linhas alteradas

**Desenvolvedor B**
- 9 commits
- 3 pull requests
- -800 linhas
- ajudou quatro colegas a resolver bloqueios

Esses números, isoladamente, não permitem concluir quem foi “mais produtivo”. Falta saber o problema resolvido, dificuldade, qualidade, colaboração, contexto e impacto.

---

## Framework SPACE

O artigo-âncora, *The SPACE of Developer Productivity* (Forsgren et al., 2021), organiza produtividade em cinco dimensões:

- **S — Satisfaction and Well-being:** satisfação e bem-estar;
- **P — Performance:** resultados e desempenho;
- **A — Activity:** atividade observável;
- **C — Communication and Collaboration:** comunicação e colaboração;
- **E — Efficiency and Flow:** eficiência e fluxo.

A consequência para este trabalho é importante: **três métricas não significam três dimensões**. Linhas de código, commits e pull requests continuam concentradas principalmente em atividade.

[Leia a análise do SPACE →](conteudo/02-space.md)

## Métricas e comportamento

Quando uma medida se torna alvo de recompensa ou punição, ela também altera incentivos. Uma equipe avaliada pela quantidade de tickets, por exemplo, pode ter incentivo para fragmentar tarefas; uma pessoa avaliada por commits pode mudar a granularidade dos commits sem necessariamente gerar mais valor.

Por isso, além de perguntar **“o que esta métrica mede?”**, é necessário perguntar:

> **“O que as pessoas terão incentivo para fazer quando descobrirem que estão sendo avaliadas por ela?”**

## DevEx

A perspectiva de Developer Experience muda a unidade de investigação. Em vez de atribuir imediatamente uma baixa entrega ao indivíduo, procura fatores do sistema que dificultam o trabalho.

O framework destaca três dimensões:

**Feedback loops · Cognitive load · Flow state**

Isso permite investigar espera por builds ou reviews, complexidade desnecessária, documentação, interrupções e outros obstáculos.

[Leia sobre DevEx →](conteudo/04-devex.md)

## IA e produtividade

IA generativa torna ainda menos segura a equivalência entre **volume de código** e **produtividade**. Gerar código mais rapidamente não elimina revisão, testes, integração, operação e manutenção.

O caso experimental da METR em 2025 também mostra por que percepção e resultado observado precisam ser separados. Em um estudo com 16 desenvolvedores experientes e 246 tarefas, os participantes esperavam ganhos com IA, enquanto naquele contexto experimental o tempo observado aumentou. O resultado é contextual e não deve ser generalizado para ferramentas atuais; a própria METR publicou uma atualização metodológica em 2026.

[Leia a análise de IA →](conteudo/05-ia-e-produtividade.md)

---

## O que recomendamos medir?

Em vez de um leaderboard individual, recomendamos combinar sinais de diferentes perspectivas:

| Perspectiva | Exemplos do que investigar |
|---|---|
| **Resultados** | qualidade, confiabilidade, impacto |
| **Fluxo** | espera, bloqueios, retrabalho |
| **Experiência** | satisfação, carga cognitiva, foco |
| **Colaboração** | reviews, mentoria, compartilhamento de conhecimento |
| **Atividade** | commits, PRs e tickets como contexto, não como veredito |

O conjunto exato deve depender da pergunta e da decisão que a organização pretende apoiar.

## Resposta à pergunta principal

**É possível medir aspectos do trabalho individual? Sim, em partes.**

**É possível condensar esses aspectos em um ranking confiável de produtividade? Não com uma métrica isolada — e combinar números sem considerar dimensões, contexto e incentivos não resolve automaticamente o problema.**

O melhor uso das métricas é ajudar a descobrir **como o sistema e as equipes podem produzir melhor**, em vez de apenas determinar **quem produziu mais**.

---

## Estrutura do repositório

```text
Metricas-individuais/
├── README.md
├── conteudo/
│   ├── 01-problema.md
│   ├── 02-space.md
│   ├── 03-metricas-individuais.md
│   ├── 04-devex.md
│   ├── 05-ia-e-produtividade.md
│   └── 06-conclusao.md
├── referencias/
│   └── referencias.md
└── slides/
    └── Grupo_4_Metricas_Individuais.pdf
```

> A apresentação utilizada pelo grupo está disponível em PDF na pasta `slides/`.

## Apresentação

➡️ [Abrir a apresentação em PDF](slides/Grupo_4_Metricas_Individuais.pdf)

## Referência principal

FORSGREN, N.; STOREY, M.-A.; MADDILA, C.; ZIMMERMANN, T.; HOUCK, B.; BUTLER, J. **The SPACE of Developer Productivity: There's more to it than you think.** *ACM Queue*, v. 19, n. 1, 2021. DOI: 10.1145/3454122.3454124.

➡️ [Ver todas as referências](referencias/referencias.md)

# 3. Métricas individuais: sinais, incentivos e riscos

## Métricas comuns

Entre os indicadores que podem aparecer em ferramentas de engenharia estão:

- quantidade de commits;
- linhas adicionadas ou removidas;
- pull requests;
- revisões de código;
- tickets concluídos;
- tempo de ciclo;
- tempo dedicado a determinadas atividades.

Esses dados não são automaticamente ruins. O problema é a inferência feita a partir deles.

## Exemplo: linhas de código

Mais linhas podem representar uma nova funcionalidade. Também podem representar duplicação, complexidade ou uma solução que poderia ser menor. Remover código pode ser uma contribuição valiosa quando simplifica o sistema.

Assim, “linhas produzidas” mede volume de alteração, não valor de maneira direta.

## Exemplo: commits e pull requests

A granularidade de commits depende da prática do desenvolvedor e da equipe. Duas pessoas podem produzir exatamente a mesma mudança e organizá-la em quantidades diferentes de commits.

O mesmo raciocínio vale para pull requests: quantidade não informa, sozinha, dificuldade, qualidade ou impacto.

## Quando a métrica se torna incentivo

Se uma organização associa recompensa, promoção ou punição diretamente a uma métrica, as pessoas passam a ter incentivo para otimizar o indicador.

Esse problema é frequentemente discutido por meio da **Lei de Goodhart**, resumida pela ideia de que uma medida tende a perder qualidade como medida quando se transforma em alvo.

No desenvolvimento de software, isso pode gerar comportamento como:

- fragmentar trabalho para aumentar contagens;
- preferir tarefas facilmente mensuráveis;
- evitar trabalhos importantes que não aparecem no placar;
- reduzir colaboração se ajudar outra pessoa não gerar reconhecimento;
- otimizar velocidade local sacrificando qualidade futura.

## O trabalho invisível

Mentoria, investigação, revisão, arquitetura, documentação, prevenção de incidentes e ajuda a colegas podem gerar impacto sem produzir grande quantidade de código autoral.

Isso dificulta atribuir o resultado de um produto a uma única pessoa.

## McKinsey × Beck e Orosz

A McKinsey defendeu em 2023 que produtividade de desenvolvedores pode ser medida com uma combinação de perspectivas nos níveis de sistema, equipe e indivíduo.

Kent Beck e Gergely Orosz responderam criticamente à proposta, chamando atenção para a diferença entre atividade e valor, para o custo da medição e para os incentivos criados quando indicadores são usados na avaliação de pessoas.

A posição deste trabalho não é abandonar a mensuração. É separar dois objetivos:

1. **medir para compreender e melhorar**;
2. **medir para ordenar pessoas**.

O primeiro pode produzir informação útil. O segundo exige inferências muito mais fortes e frágeis.

[← SPACE](02-space.md) · [Próximo: DevEx →](04-devex.md)

# Alocação de Horários das Partidas no Futebol

## Alunos
- Lucas Van-Lume Lima (lvll)  
- Jorge Guilherme Luna de Vasconcelos Cabral (jglvc)

## Modelagem do Problema

### Variáveis de Decisão
- **Horário da partida**: O horário exato em que cada jogo será realizado.
- **Local da partida**: O estádio em que o jogo será realizado.

### Restrições
1. **Conflitos de estádio**: Dois jogos não podem ocorrer no mesmo estádio ao mesmo tempo.
2. **Descanso dos times**: Deve haver um intervalo mínimo entre os jogos de um mesmo time.
3. **Horários preferenciais**: Partidas de maior apelo devem ocorrer em horários nobres, mas é importante garantir que todos os times tenham oportunidades similares de jogar nesses horários.
4. **Equidade de confrontos**: Distribuir uniformemente jogos contra adversários de alto desempenho, evitando que um time enfrente várias partidas consecutivas contra equipes de alto nível.
5. **Viagens**: Garantir que nenhum time jogue muitas partidas consecutivas fora de casa ou percorra longas distâncias repetidamente.

### Função Objetivo
1. **Minimizar conflitos**: Reduzir ao máximo os conflitos de horário e local.
2. **Maximizar audiência**: Escolher horários que favoreçam maior audiência.
3. **Reduzir custos logísticos**: Diminuir as viagens longas ou desnecessárias.

## Justificativa do Tema
Resolver esse tipo de problema traz benefícios significativos para torcedores, jogadores e o setor administrativo das equipes de futebol. Um planejamento mais eficiente permite:

- **Otimizar o uso dos estádios**: Garantir maior ocupação e reduzir a ociosidade.
- **Atrair uma audiência mais ampla**: Alocar partidas em horários estrategicamente definidos.
- **Minimizar o desgaste físico dos atletas**: Garantir intervalos apropriados entre partidas e viagens mais organizadas.
- **Fortalecer a credibilidade das competições**: Promover um calendário de jogos mais equilibrado e justo, evitando privilégios a qualquer equipe.

## Como se Encaixa no Contexto de Otimização?
O problema de alocação de horários e locais para partidas de futebol está diretamente relacionado ao campo da otimização, pois envolve a busca pela melhor solução entre diversas possibilidades, considerando:

- Múltiplas **restrições** como logística, conforto e preferências.
- **Objetivos conflitantes**, como minimizar custos e maximizar audiência.
- **Equilíbrio de interesses** entre torcedores, jogadores e organizadores.

A solução ideal permite o uso eficiente dos recursos, melhorando a experiência de todos os envolvidos na competição.


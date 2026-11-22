# Relatório de Desempenho de Clube (2026)

Projeto de análise de dados esportivos desenvolvido no Power BI, estruturado com navegação por botões e três páginas principais (Visão Geral, Elenco e Jogadores) para acompanhar o desempenho coletivo e individual na temporada de 2026.

---

## Objetivo do Projeto

Consolidar métricas esportivas da temporada de 2026 para responder a perguntas de desempenho e análise de jogo:
- Qual é o aproveitamento geral, o saldo de gols, o desempenho por competição e o recorte Casa x Fora?
- Quais atletas lideram em gols, assistências, participações diretas (G+A), minutos jogados e cartões?
- Como se compara o rendimento individual de um jogador específico frente à média da sua posição?

---

## Ferramentas e Abordagem

- **Power BI e DAX:** criação de medidas de aproveitamento, médias, participação em gols (G+A), taxa de conversão e comparativos com a média por posição.
- **Navegação e Filtros:** botões de navegação entre páginas, filtros laterais por Mês, Competição, Mando, Posição e Jogador.
- **Páginas do relatório:** Visão Geral, Elenco e Jogadores.

---

## Estrutura do Dashboard

### 1. Visão Geral (Clube)
Consolidação do desempenho coletivo em 2026:
- **KPIs:** 48 jogos, 31 vitórias, 9 empates, 8 derrotas, média de 1,73 gols marcados, 0,73 gols sofridos, saldo de 1,00 gol/jogo e 70,83% de aproveitamento geral.
- **Competições e evolução:** gols marcados x sofridos e aproveitamento por competição (Campeonato Paulista com 80,00%, Copa do Brasil com 75,00%, Brasileirão com 71,21% e Libertadores com 47,62%), além da evolução mensal do aproveitamento.
- **Casa x Fora e jogos recentes:** desempenho em Casa (84,00% de aproveitamento em 25 jogos) vs. Fora (56,52% em 23 jogos) e tabela dos últimos 5 jogos.

### 2. Elenco
Visão agregada dos atletas na temporada:
- **KPIs:** 25 jogadores, 83 gols, 52 assistências, 92 cartões amarelos, 1 cartão vermelho, 19.790 passes certos, 291 finalizações e 135 participações em gols (G+A).
- **Destaques e distribuições:** Top 5 artilheiros (liderado por Flaco López com 19 gols), Top 5 assistentes (Andreas Pereira e Flaco López com 10), cartões por jogador, distribuição de gols por posição (ATA com 44 / 53,01% e MEI com 30 / 36,14%), minutos jogados e ranking de G+A (Flaco López com 29).

### 3. Jogadores
Análise individual filtrável por atleta (exemplo exibido: Flaco López):
- **KPIs individuais:** 42 jogos, 19 gols, 10 assistências, 3.100 minutos jogados, 51 chutes certos, 33,33% de taxa de conversão e 29 participações em gols (G+A).
- **Comparativos e detalhamento:** chutes certos e passes certos do jogador vs. média da posição (ATA), proporção de gols vs. assistências (65,52% vs. 34,48%), cartões e tabela consolidada com métricas como minutos por participação (114,81).

---

## Principais Observações do Painel

- O desempenho em Casa (84,00% de aproveitamento) supera de forma expressiva o rendimento Fora (56,52%).
- Entre as competições exibidas, o Campeonato Paulista apresenta o maior aproveitamento (80,00%), enquanto a Libertadores registra o menor (47,62%).
- No recorte do elenco, os atacantes respondem por 53,01% dos gols (44 de 83), com destaque individual de Flaco López em gols e G+A.

---

## Como Abrir o Arquivo

1. Faça o download do arquivo `.pbix` deste repositório.
2. Abra o arquivo no Power BI Desktop.
3. Utilize os botões superiores (Visão Geral, Elenco e Jogadores) e os filtros laterais para explorar os dados.

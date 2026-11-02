# Onze Ideal 26/27 — Pacote 2.13

## Reformulação da aba Competições
- Central de competições com navegação compacta e contagem de participantes.
- Participantes listados com escudos/imagens cadastrados; clubes sem imagem cadastrada recebem identificação alternativa com sigla e cores, sem apresentar o fallback como escudo oficial.
- Calendários próprios para Série A, Série B, Série C, Série D e Copa do Brasil.
- Datas de rodadas calculadas a partir do ano da carreira; a temporada 1 começa em 2026 e a temporada seguinte em 2027.
- Calendários de liga respeitam os jogos, resultados e rodadas já registrados na carreira.
- Ajuste no chaveamento da Copa do Brasil para que equipes com bye não sejam descartadas em fases com número ímpar de classificados.
- Atualização dos participantes da Copa do Brasil para refletir os 156 clubes cadastrados no universo atual do jogo.

## Verificações
- JavaScript validado com `node --check`.
- Testes automatizados de quantidade de clubes (20/20/20/96), número de partidas por rodada, virada de temporada e conclusão do mata-mata com 156 participantes.
- O teste visual completo em navegador não pôde ser concluído neste ambiente.

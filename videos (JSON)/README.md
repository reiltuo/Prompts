# Prompts de vídeo em JSON

Esta pasta contém os 8 prompts da pasta `videos` do repositório `reiltuo/Prompts`, remodelados em JSON detalhado.

## Estrutura

Cada prompt possui seu próprio arquivo JSON. O `manifest.json` funciona como índice da coleção.

Os arquivos foram estruturados para separar com clareza:

* objetivo principal
* requisitos da imagem de referência
* formato de saída
* comportamento de câmera
* preservação do cenário
* ações e sequência temporal
* biomecânica e física
* continuidade entre frames
* restrições negativas
* ordem de prioridades

## Fidelidade

Cada JSON registra o caminho, o commit e o hash SHA-256 do arquivo TXT usado como fonte. Isso permite identificar exatamente qual versão originou a conversão.

O texto `916` presente em algumas fontes foi normalizado como proporção `9:16`, que corresponde ao contexto de vídeo vertical. Nenhuma ação narrativa nova foi adicionada. Detalhes implícitos foram explicitados apenas quando necessários para proteger anatomia, continuidade, física e composição.

No prompt 03, o título da fonte menciona apontar para baixo, mas o corpo pede repetidamente o canto inferior esquerdo. O JSON preserva o canto inferior esquerdo e documenta essa decisão.

## Compatibilidade

Os arquivos são JSON padrão e não dependem de um gerador específico. Plataformas diferentes podem exigir a conversão dos campos para um único texto ou para parâmetros próprios da API.

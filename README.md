# Biblioteca de prompts realistas

Prompts organizados por tipo de uso. Cada item tem uma página visual em `.md` e um arquivo `.txt` cru para copiar e colar rápido.

## Como usar

1. Escolha `Imagens` ou `Vídeos`.
2. Clique no nome do prompt para ver a explicação e o bloco completo.
3. Clique em `TXT` para abrir só o prompt cru.

## Imagens

| Prompt | O que faz | TXT |
|---|---|---|
| [Imagem com modelo, ambiente e roupa](imagens/01-imagem-modelo-ambiente-roupa.md) | Combina ambiente, pose, identidade do avatar e roupa para criar uma imagem realista de moda. | [TXT](imagens/txt/01-imagem-modelo-ambiente-roupa.txt) |
| [Analisar imagem em JSON](imagens/02-analisar-imagem-em-json.md) | Analisa uma imagem de referência e gera uma descrição estruturada em JSON com alta fidelidade visual. | [TXT](imagens/txt/02-analisar-imagem-em-json.txt) |
| [Upscale fiel da imagem](imagens/03-upscale-fiel-da-imagem.md) | Cria uma versão mais nítida e detalhada da mesma imagem, sem mudar cena, identidade ou composição. | [TXT](imagens/txt/03-upscale-fiel-da-imagem.txt) |
| [Recriar cenário brasileiro simples](imagens/04-recriar-cenario-brasileiro-simples.md) | Reinterpreta o ambiente como casa brasileira simples de baixa renda e retorna uma especificação em JSON. | [TXT](imagens/txt/04-recriar-cenario-brasileiro-simples.txt) |
| [Nova cena com a mesma modelo](imagens/05-nova-cena-com-mesma-modelo.md) | Mantém a identidade da modelo e cria uma nova cena com outro contexto e enquadramento mais próximo. | [TXT](imagens/txt/05-nova-cena-com-mesma-modelo.txt) |
| [Criar cena com JSON de referência](imagens/06-criar-cena-com-json-de-referencia.md) | Gera uma nova composição com a mesma modelo usando uma referência de cenário em JSON. | [TXT](imagens/txt/06-criar-cena-com-json-de-referencia.txt) |
| [Ajustar enquadramento e zoom](imagens/07-ajustar-enquadramento-e-zoom.md) | Altera proximidade da câmera e enquadramento mantendo identidade, estilo e consistência visual. | [TXT](imagens/txt/07-ajustar-enquadramento-e-zoom.txt) |
| [Colagem facial consistente](imagens/08-colagem-facial-consistente.md) | Cria um conjunto de imagens mantendo a identidade facial travada em diferentes composições. | [TXT](imagens/txt/08-colagem-facial-consistente.txt) |
| [Colagem de referências visuais](imagens/09-colagem-de-referencias-visuais.md) | Gera uma colagem de referências para manter consistência de pessoa, roupa, ambiente e estilo. | [TXT](imagens/txt/09-colagem-de-referencias-visuais.txt) |
| [Extrair pose da imagem](imagens/10-extrair-pose-da-imagem.md) | Extrai pose, linguagem corporal e composição para reutilizar como referência. | [TXT](imagens/txt/10-extrair-pose-da-imagem.txt) |
| [Extrair roupa em JSON](imagens/11-extrair-roupa-em-json.md) | Extrai detalhes da roupa, como modelagem, tecido, cor, caimento e pontos visuais importantes. | [TXT](imagens/txt/11-extrair-roupa-em-json.txt) |
| [Criar poses com produto](imagens/12-criar-poses-com-produto.md) | Cria poses com produto mantendo campos travados e consistência visual para geração de imagem. | [TXT](imagens/txt/12-criar-poses-com-produto.txt) |
| [Trocar pose mantendo cena](imagens/13-trocar-pose-mantendo-cena.md) | Troca a pose da pessoa mantendo ambiente, roupa, identidade e estilo da imagem de referência. | [TXT](imagens/txt/13-trocar-pose-mantendo-cena.txt) |

## Vídeos

| Prompt | O que faz | TXT |
|---|---|---|
| [Vídeo de influenciadora mostrando roupa](videos/01-video-influenciadora-mostrando-roupa.md) | Cria um vídeo realista de influenciadora mostrando roupa com câmera fixa, movimentos naturais e sem fala. | [TXT](videos/txt/01-video-influenciadora-mostrando-roupa.txt) |
| [Vídeo aproximando da câmera](videos/02-video-aproximando-da-camera.md) | Cria um vídeo em que a influenciadora se aproxima da câmera mantendo cenário, roupa e enquadramento estáveis. | [TXT](videos/txt/02-video-aproximando-da-camera.txt) |
| [Vídeo CTA apontando para baixo](videos/03-video-cta-apontando-para-baixo.md) | Cria um encerramento visual com sorriso natural e gesto de chamada para ação apontando para baixo. | [TXT](videos/txt/03-video-cta-apontando-para-baixo.txt) |
| [POV com mão gesticulando sem tocar](videos/04-pov-mao-gesticulando-sem-tocar.md) | Cria vídeo POV de TikTok Shop com mão feminina gesticulando ao lado da roupa sem tocar no produto. | [TXT](videos/txt/04-pov-mao-gesticulando-sem-tocar.txt) |
| [POV com mão tocando o tecido](videos/05-pov-mao-tocando-o-tecido.md) | Cria vídeo POV com mão feminina tocando, alisando e mostrando textura do tecido. | [TXT](videos/txt/05-pov-mao-tocando-o-tecido.txt) |
| [Vídeo com movimento natural de moda](videos/06-video-movimento-natural-de-moda.md) | Anima uma modelo com movimento contínuo, natural e levemente rápido, sem giro e sem congelar. | [TXT](videos/txt/06-video-movimento-natural-de-moda.txt) |
| [Vídeo mexendo no cabelo](videos/07-video-mexendo-no-cabelo.md) | Cria vídeo POV de moda com passos curtos, toque na roupa, ajuste no cabelo e expressões humanas naturais. | [TXT](videos/txt/07-video-mexendo-no-cabelo.txt) |
| [Vídeo CTA para Moda TikTok Shop](videos/08-video-cta-moda-tiktok-shop.md) | Cria vídeo CTA em 9:16 com sorriso, passo para frente e dedo apontando para baixo sem fala. | [TXT](videos/txt/08-video-cta-moda-tiktok-shop.txt) |

## Estrutura

- `imagens/`: prompts para criação, análise, edição, pose, roupa, cenário e colagens de imagem.
- `videos/`: prompts para animação, apresentação de produto, POV, movimento natural e CTA.
- `imagens/txt/` e `videos/txt/`: versões cruas para copiar direto.

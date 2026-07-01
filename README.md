# Biblioteca de prompts realistas

Prompts organizados por tipo de uso. Cada item tem uma página visual em `.md` e um arquivo `.txt` cru para copiar e colar rápido.

## Como usar

1. Escolha `Imagens` ou `Vídeos`.
2. Clique no nome do prompt para ver a explicação e o bloco completo.
3. Clique em `TXT` para abrir só o prompt cru.
4. Abra `videos (JSON)` para usar as versões estruturadas e detalhadas dos prompts de vídeo.

## Imagens

| Prompt | O que faz | TXT |
|---|---|---|
| [Criar modelo e look](imagens/01-criar-modelo-e-look.md) | Combina ambiente, pose, identidade do avatar e roupa para criar uma imagem realista de moda. | [TXT](imagens/txt/01-criar-modelo-e-look.txt) |
| [Analisar imagem em JSON](imagens/02-analisar-imagem-json.md) | Analisa uma imagem de referência e gera uma descrição estruturada em JSON com alta fidelidade visual. | [TXT](imagens/txt/02-analisar-imagem-json.txt) |
| [Melhorar imagem](imagens/03-melhorar-imagem.md) | Cria uma versão mais nítida e detalhada da mesma imagem, sem mudar cena, identidade ou composição. | [TXT](imagens/txt/03-melhorar-imagem.txt) |
| [Recriar cenário](imagens/04-recriar-cenario.md) | Reinterpreta o ambiente como casa brasileira simples de baixa renda e retorna uma especificação em JSON. | [TXT](imagens/txt/04-recriar-cenario.txt) |
| [Criar nova cena](imagens/05-criar-nova-cena.md) | Mantém a identidade da modelo e cria uma nova cena com outro contexto e enquadramento mais próximo. | [TXT](imagens/txt/05-criar-nova-cena.txt) |
| [Criar cena com JSON](imagens/06-criar-cena-com-json.md) | Gera uma nova composição com a mesma modelo usando uma referência de cenário em JSON. | [TXT](imagens/txt/06-criar-cena-com-json.txt) |
| [Ajustar enquadramento](imagens/07-ajustar-enquadramento.md) | Altera proximidade da câmera e enquadramento mantendo identidade, estilo e consistência visual. | [TXT](imagens/txt/07-ajustar-enquadramento.txt) |
| [Criar colagem facial](imagens/08-criar-colagem-facial.md) | Cria um conjunto de imagens mantendo a identidade facial travada em diferentes composições. | [TXT](imagens/txt/08-criar-colagem-facial.txt) |
| [Criar colagem visual](imagens/09-criar-colagem-visual.md) | Gera uma colagem de referências para manter consistência de pessoa, roupa, ambiente e estilo. | [TXT](imagens/txt/09-criar-colagem-visual.txt) |
| [Extrair pose](imagens/10-extrair-pose.md) | Extrai pose, linguagem corporal e composição para reutilizar como referência. | [TXT](imagens/txt/10-extrair-pose.txt) |
| [Extrair roupa em JSON](imagens/11-extrair-roupa-json.md) | Extrai detalhes da roupa, como modelagem, tecido, cor, caimento e pontos visuais importantes. | [TXT](imagens/txt/11-extrair-roupa-json.txt) |
| [Criar poses com produto](imagens/12-criar-poses-com-produto.md) | Cria poses com produto mantendo campos travados e consistência visual para geração de imagem. | [TXT](imagens/txt/12-criar-poses-com-produto.txt) |
| [Trocar pose](imagens/13-trocar-pose.md) | Troca a pose da pessoa mantendo ambiente, roupa, identidade e estilo da imagem de referência. | [TXT](imagens/txt/13-trocar-pose.txt) |

## Vídeos

| Prompt | O que faz | TXT |
|---|---|---|
| [Mostrar roupa](videos/01-mostrar-roupa.md) | Cria um vídeo realista de influenciadora mostrando roupa com câmera fixa, movimentos naturais e sem fala. | [TXT](videos/txt/01-mostrar-roupa.txt) |
| [Aproximar da câmera](videos/02-aproximar-da-camera.md) | Cria um vídeo em que a influenciadora se aproxima da câmera mantendo cenário, roupa e enquadramento estáveis. | [TXT](videos/txt/02-aproximar-da-camera.txt) |
| [CTA apontar para baixo](videos/03-cta-apontar-para-baixo.md) | Cria um encerramento visual com sorriso natural e gesto de chamada para ação apontando para baixo. | [TXT](videos/txt/03-cta-apontar-para-baixo.txt) |
| [Mão gesticular sem tocar](videos/04-mao-gesticular-sem-tocar.md) | Cria vídeo POV de TikTok Shop com mão feminina gesticulando ao lado da roupa sem tocar no produto. | [TXT](videos/txt/04-mao-gesticular-sem-tocar.txt) |
| [Mão tocar no tecido](videos/05-mao-tocar-no-tecido.md) | Cria vídeo POV com mão feminina tocando, alisando e mostrando textura do tecido. | [TXT](videos/txt/05-mao-tocar-no-tecido.txt) |
| [Movimento natural](videos/06-movimento-natural.md) | Anima uma modelo com movimento contínuo, natural e levemente rápido, sem giro e sem congelar. | [TXT](videos/txt/06-movimento-natural.txt) |
| [Ajustar cabelo](videos/07-ajustar-cabelo.md) | Cria vídeo POV de moda com passos curtos, toque na roupa, ajuste no cabelo e expressões humanas naturais. | [TXT](videos/txt/07-ajustar-cabelo.txt) |
| [CTA TikTok Shop](videos/08-cta-tiktok-shop.md) | Cria vídeo CTA em 9:16 com sorriso, passo para frente e dedo apontando para baixo sem fala. | [TXT](videos/txt/08-cta-tiktok-shop.txt) |

## Vídeos em JSON

| Prompt | O que faz | JSON |
|---|---|---|
| Mostrar roupa | Apresentação ágil e natural de roupa com câmera e cenário totalmente fixos. | [JSON](videos%20%28JSON%29/01-mostrar-roupa.json) |
| Aproximar da câmera | Aproximação, recuo e ângulos corporais sutis com câmera fixa. | [JSON](videos%20%28JSON%29/02-aproximar-da-camera.json) |
| CTA apontar para baixo | CTA silencioso com aproximação, sorriso e apontar para o canto inferior esquerdo. | [JSON](videos%20%28JSON%29/03-cta-apontar-para-baixo.json) |
| Mão gesticular sem tocar | Gestos conversacionais Ã  direita sem contato com o produto. | [JSON](videos%20%28JSON%29/04-mao-gesticular-sem-tocar.json) |
| Mão tocar no tecido | Demonstração tátil com interação e física realista do tecido. | [JSON](videos%20%28JSON%29/05-mao-tocar-no-tecido.json) |
| Movimento natural | Movimento corporal contínuo perto do ponto inicial, sem rotação ou pausa. | [JSON](videos%20%28JSON%29/06-movimento-natural.json) |
| Ajustar cabelo | Aproximação, toque no laço, recuo, expressões alternadas e ajuste do cabelo. | [JSON](videos%20%28JSON%29/07-ajustar-cabelo.json) |
| CTA TikTok Shop | CTA de oito segundos com sorriso, inclinação, dolly-in e indicador apontando para baixo. | [JSON](videos%20%28JSON%29/08-cta-tiktok-shop.json) |

[Abrir manifesto da coleção JSON](videos%20%28JSON%29/manifest.json)

## Estrutura

- `imagens/`: prompts para criação, análise, edição, pose, roupa, cenário e colagens de imagem.
- `videos/`: prompts para animação, apresentação de produto, POV, movimento natural e CTA.
- `imagens/txt/` e `videos/txt/`: versões cruas para copiar direto.
- `videos (JSON)/`: versões estruturadas e detalhadas dos 8 prompts de vídeo, com manifesto e documentação próprios.


## Coleção Grok para vídeo de moda

Coleção com 7 aberturas sem repetição, 5 vídeos de 10 segundos e 5 sequências completas em JSON.

[Abrir coleção Grok](videos%20%28JSON%29/grok-video-moda/README.md)

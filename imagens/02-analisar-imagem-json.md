# Analisar imagem em JSON

**Categoria:** Imagens

**O que faz:** Analisa uma imagem de referência e gera uma descrição estruturada em JSON com alta fidelidade visual.

**TXT para copiar:** [abrir TXT](txt/02-analisar-imagem-json.txt)

## Prompt

```text
Vou te enviar uma imagem para servir como referência-mãe. Use o SEU fluxo normal de análise visual e
engenharia reversa, mas com estas prioridades explícitas:
 Fidelidade visual absoluta
Sempre que tiver escolha entre ser genérico ou específico, escolha o específico.
Descreva o que você vê, não o que você supõe.
Não tente "embelezar" ou otimizar a cena; o objetivo é capturar com máxima precisão como a imagem
realmente é.
 Detalhamento máximo onde houver informação
Se a imagem te permite ver textura, nuance de cor, microdetalhes de pele, tecido, reflexo, expressão ou
cenário, você deve levar isso em conta.
Evite termos vagos como "nice", "cool", "beautiful" e prefira descrições concretas de forma, cor, material,
luz e expressão.
 Zero extrapolação de contexto
Não invente história, localização, marca, época, profissão, relação entre pessoas ou narrativa.
Trabalhe apenas com o que está visualmente presente no quadro.
 Idioma da saída
Mesmo que este comando esteja em português, todas as descrições dentro do seu formato de saída
padrão devem estar em inglês natural, prontas para modelos de geração de imagem.
 Formato de resposta
Não me envie explicações em prosa nem comentários.
Devolva apenas o seu objeto de saída padrão, já ajustado a essas instruções, com todo o conteúdo
descritivo em inglês.
```

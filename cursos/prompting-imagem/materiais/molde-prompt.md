# Molde do prompt em camadas

Use este molde para escrever qualquer imagem do seu projeto. Troque tudo o que está entre `< >`. Escreva o prompt final em **inglês** e em **texto corrido** (não em tópicos) — é o que os geradores seguem melhor.

## 1. Checklist das camadas

| Camada | Pergunta | Exemplo (Terra Alta) |
|---|---|---|
| Sujeito + ação | Quem está no quadro, como é, o que faz agora? | Lia, barista, 30 e poucos, cabelo cacheado preso, sardas, avental de linho mostarda, despejando água no coador |
| Plano / ângulo | Quanto se vê e de onde? | medium shot, eye level |
| Lente | Quanto espaço, quanta compressão? | 50mm lens at f/2 |
| Luz | Fonte, direção, qualidade, temperatura | soft morning window light from the left, warm 3500K |
| Textura | Quais materiais precisam parecer tocáveis? | matte glazed ceramic, linen apron, worn wooden counter |
| Composição | Onde fica o sujeito, onde sobra espaço? | subject on the left third, negative space on the right |
| Estilo | Época, gênero, suporte (descritos, sem nomes de artistas) | natural documentary photography, subtle 35mm film grain |
| Emoção | O que o espectador deve sentir? | evoking quiet craftsmanship at dawn |

## 2. Molde em texto corrido

```
<Plano> of <sujeito: quem, aparência, roupa> <ação física concreta>, in <lugar com 2-3 objetos>.
Shot on a <lente> lens at <abertura>, <ângulo>.
<Fonte de luz> from the <direção>, <qualidade> light, <temperatura>K.
Detailed textures: <material 1 + 2 adjetivos>, <material 2 + 2 adjetivos>.
<Composição: posição do sujeito, espaço negativo, camadas>.
<Referência de estilo: época, gênero, suporte>, evoking <emoção pretendida>.
```

## 3. Molde de edição ("muda só X")

```
Change ONLY the <camada: lighting | framing | lens | composition> to <nova escolha, descrita em detalhe>.
Keep the same person, face, outfit, pose, objects, background and color grade identical.
```

Para mudanças grandes de estilo ou ângulo, seja enfático: `Fully re-render this ENTIRE image as…` / `Completely re-shoot this scene from…`.

## 4. Molde de peça de série com referência de identidade

```
Use the person in the attached image as a strict identity reference (same face, <traços>, <cabelo>, <figurino>) and completely re-shoot a NEW photo:
<plano> of <ação> in <lugar>.
<lente> lens at <abertura>, <ângulo>.
<CONSTANTE DE LUZ DO PRESET>.
<CONSTANTE DE TEXTURAS DO PRESET>.
<composição>.
<CONSTANTE DE ESTILO E PALETA DO PRESET>.
<NEGATIVOS DO PRESET>.
```

## 5. O mesmo prompt em JSON

Útil em geradores que aceitam instruções estruturadas (confira na sua ferramenta). Para variar, troque um campo e mantenha o resto.

```json
{
  "subject": {
    "who": "<quem, idade aproximada, cabelo, pele, traços>",
    "wardrobe": "<roupa>",
    "action": "<ação física concreta>",
    "expression": "<expressão visível>"
  },
  "camera": { "shot": "<plano>", "angle": "<ângulo>", "lens": "<mm>", "aperture": "<f/>" },
  "lighting": { "source": "<fonte>", "direction": "<direção>", "quality": "<soft | hard>", "temperature": "<K>" },
  "materials": ["<material 1>", "<material 2>", "<material 3>"],
  "composition": { "placement": "<posição>", "negative_space": "<onde>", "background": "<fundo>" },
  "palette": ["#HEX nome", "#HEX nome"],
  "style": "<época, gênero, suporte>",
  "negative": "<o que evitar>",
  "mood": "<emoção pretendida>"
}
```

## 6. Ciclo de comparação (depois de cada geração)

1. **Gere** a partir de um prompt salvo.
2. **Compare** com a referência ou a versão anterior, lado a lado.
3. **Nomeie** a diferença com vocabulário técnico.
4. **Refine** uma camada só.
5. **Salve** o prompt vencedor com a imagem.

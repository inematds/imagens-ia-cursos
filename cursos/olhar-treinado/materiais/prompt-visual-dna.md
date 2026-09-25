# Prompt — extrair o DNA visual de uma marca

Use com um assistente que aceite imagens (ChatGPT, Claude, Gemini). Anexe de 6 a 12 imagens que representam a marca hoje (posts, fotos de produto, site, embalagem) **ou** as referências que você quer atingir. Preencha o que está entre `< >`.

O resultado é a **Legenda de DNA Visual**: uma única fonte de verdade com as decisões de cor, forma, composição, tipografia, textura e estilo de imagem — cada uma ligada à emoção que deve provocar.

---

## Prompt (copie e cole)

```
Você é diretor de arte e vai montar a Legenda de DNA Visual de uma marca.

MARCA: <nome e o que faz, em 2 frases>
PÚBLICO: <quem compra / quem deve confiar>
OBJETIVO PRINCIPAL: <vender / atrair clientes / gerar confiança e autoridade / mobilizar>
3 PALAVRAS DE VIBE (norte da marca): <ex.: artesanal, caloroso, preciso>
ONDE AS IMAGENS APARECEM: <feed, site, anúncios, embalagem>

Analise as imagens anexadas e responda em 6 partes.

1) LEITURA ATUAL — Para cada imagem, uma linha: qual elemento mais pesa e que efeito ele produz (formato "elemento → efeito").

2) CADEIA DE SIGNIFICADO — Para cada elemento-chave abaixo, escreva a cadeia
   Elemento → função prática → meta-mensagem → emoção que provoca:
   - cor de base
   - cor de acento
   - forma dominante (arredondada, angular, geométrica, orgânica)
   - composição (espaço negativo, simetria/assimetria, um herói ou vários)
   - textura e acabamento (grão, brilho, papel, cromado)
   - estilo de imagem (produto em estúdio, lifestyle espontâneo, luz cinematográfica, macro)
   - tipografia, se houver (serifada, sem serifa, pesada, leve)

3) COERÊNCIA — Quais elementos puxam para as 3 palavras de vibe e quais puxam para outro lado? Liste os conflitos em ordem de gravidade.

4) PALETA COM PAPÉIS — Proponha: base neutra (1–2 cores), acento principal (1 cor), acento de apoio (opcional, uso raro). Dê um nome descritivo e um HEX aproximado para cada, e onde cada uma deve aparecer.

5) LEGENDA DE DNA VISUAL — Uma tabela com: Elemento | Decisão | Por quê (emoção) | Nunca fazer.
   Cubra: cor, forma, composição, luz, textura, estilo de imagem, tipografia.

6) BLOCO DE ESTILO — Escreva um STYLE BLOCK de 3 a 5 linhas, em inglês, pronto para colar no fim de prompts de imagem, que aplique essa legenda (luz com direção, paleta com acento único, lente, textura, clima).

Regras: não cite artistas, fotógrafos ou marcas reais como referência de estilo; descreva a estética com palavras. Seja específico e verificável — nada de "bonito", "moderno" ou "profissional" sem dizer o que isso é na imagem.
```

---

## Como conferir a resposta

- A cadeia de cada elemento termina numa emoção **coerente com as 3 palavras de vibe**? Se não, o elemento é candidato a sair.
- A paleta tem **um** acento principal? Se o assistente propôs três acentos, peça para escolher um.
- O bloco de estilo tem luz com fonte e direção, paleta com acento único, lente e textura? Teste-o gerando 3 imagens de assuntos diferentes (pessoa, produto, ambiente) e veja se parecem da mesma marca.
- Guarde a legenda com data e versão. Revise a cada trimestre ou quando o objetivo da marca mudar.

## Referência rápida: cores e o que costumam sugerir

| Cor | Tende a sugerir | Cuidado |
|---|---|---|
| Azul | confiança, estabilidade | frio sem toque humano |
| Vermelho | urgência, energia | agressivo em área grande |
| Verde | crescimento, saúde | "bem-estar genérico" em excesso |
| Amarelo / laranja | otimismo, calor | reduz o premium em área grande |
| Roxo | criatividade, aspiração | infantil se muito saturado |
| Preto / branco | autoridade, contenção | precisa de contraste e respiro |
| Marrom / bege | artesanal, herança | pode envelhecer a marca |
| Ciano / turquesa | inovação calma | neon demais vira balada |
| Cinza | neutralidade, maturidade | frio sem um acento quente |

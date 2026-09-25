# Prompts-chave da campanha — moldes

Troque tudo o que está entre < >. Os prompts estão em inglês porque é o que os modelos seguem melhor.
Regra geral: **objeto primeiro, depois contexto, depois técnica**; nas edições, diga o que muda e o que fica.

---

## Blocos fixos (cole sempre iguais)

### DNA fixo do personagem
```
<Nome>, <idade>, from <lugar>: <pele e subtom>, <traços do rosto>, <olhos>, <marca distintiva: pinta, sardas, cicatriz>, <cabelo: textura, comprimento, repartido>, <acessório fixo>.
```

### Bloco do produto (quando o produto entra por descrição)
```
a <formato do produto> with <cor principal> (<HEX>) <material/acabamento>, a <cor 2> (<HEX>) <elemento gráfico>, the wordmark '<NOME>' in <descrição tipográfica> and <detalhe do rótulo>
```

### Frase de proteção (fim de toda edição)
```
Keep the <produto>'s shape, <elementos do rótulo>, the <NOME> wordmark, the <cor 1> and <cor 2> colors, the camera angle and framing exactly the same. No other text.
```

---

## 1. Bases

### Packshot do produto (geração)
```
Studio packshot of a single <produto> standing upright, perfectly frontal at eye level, centered on a seamless pure white background. <Descrição completa do rótulo com HEX e wordmark entre aspas>. Soft diffused light from a large softbox above-left, soft contact shadow. 85mm lens at f/8, everything in sharp focus, no props. Clean e-commerce product photography, true-to-color.
```

### Personagem de referência (geração)
```
Waist-up studio portrait of <DNA fixo>. She/He wears <roupa neutra>. Relaxed, confident expression, looking straight at the camera. Seamless light-grey studio background. Large soft key light from front-left, gentle fill. 85mm lens at f/4, eye level. Natural skin texture with visible pores, no heavy retouching. Clean character reference photograph.
```

---

## 2. Fotos de produto (edição da base)
```
Completely re-shoot this exact <produto> as a <LOW-ANGLE hero shot / TOP-DOWN shot / MACRO PROFILE shot / THREE-QUARTER VIEW>: <situação com 3 detalhes físicos>. <Lente e abertura>, <luz: fonte, direção, qualidade>. <Frase de proteção>
```

## 3. Exploração criativa (um eixo por edição)
```
Change ONLY the <weather / light source / mood> of this image: <nova situação com 2-3 detalhes físicos>. The <produto> stays in exactly the same position and size. <Frase de proteção>
```
```
Fully re-render this ENTIRE image as if everything were made of <material: knitted wool / translucent jelly / white marble / piles of fruit>: <como o produto e o cenário ficam nesse material>, the '<NOME>' wordmark still clearly readable. Keep the silhouette, proportions, frontal angle and framing.
```

## 4. Personagem + produto (edição da base do personagem)
```
Keep this exact <woman/man> — <DNA fixo>. Place her/him in a completely new scene: <lugar e hora>, <ação>, holding <bloco do produto>. <Plano>, <lente>, <ângulo>, <luz>. No other text.
```

## 5. Várias referências com papéis
```
<Ação e cena em 1 frase>.
Use the face from reference image 1 exactly, preserve identity and facial structure.
Use the full outfit from reference image 2 exactly, no changes to clothing.
Use the location from reference image 3 exactly, same layout and objects.
Use the object from reference image 4 exactly, <onde está / como é segurado>.
<Plano>, <lente>, <luz>. NO text, NO labels, NO grid, NO extra people.
```

## 6. Texto e marca
### Peça com slogan
```
Turn this into a finished <billboard / square poster / story> ad for <marca>, keeping <o que fica da imagem>. Background: <cor> (<HEX>) with <elemento gráfico>. Headline '<SLOGAN>' in a <descrição tipográfica>, <cor> (<HEX>), <posição>. Below it '<NOME>' in <cor> and a small line '<linha de apoio>'. Clean layout, generous margins. Every text spelled exactly as written, no other text.
```
### Trocar cor ou fonte numa peça pronta
```
Change ONLY the <headline color / font> to <HEX / descrição da fonte>. Keep the text, layout, image and everything else identical.
```
### Corrigir uma palavra
```
Change ONLY the word '<ERRADA>' to '<CERTA>', same font, size, color and position. Keep everything else identical.
```
### Localizar para outro idioma
```
Translate ONLY the texts in this ad into <idioma>: '<texto 1>' becomes '<tradução 1>', '<texto 2>' becomes '<tradução 2>'. Keep the same font style, size, color, position and everything else identical.
```
### Infográfico
```
Turn this into a technical infographic in the style of a clean engineering drawing on <cor> paper, fine <cor> line work with <cores de marca> accents. Center: <personagem/produto>. <N> numbered callouts with thin leader lines: '1. <rótulo>' pointing at <parte>, '2. <rótulo>' pointing at <parte>, '3. <rótulo>' pointing at <parte>. Title at the top: '<TÍTULO>'. Every text spelled exactly as written, no other text.
```

## 7. Storyboard
```
Using the <woman/man> in the attached image as the protagonist — <DNA fixo> in every panel — create a 6-panel cinematic storyboard in a clean 2x3 grid, thin white gutters, each panel numbered 1 to 6 in its top-left corner. Photorealistic film stills, consistent <grade de cor>, <cenário>.
1. <Plano geral>: <situação>.
2. <Plano médio>: <desejo / produto aparece>.
3. <Plano-detalhe>: <gatilho>.
4. <Close>: <virada / reação>.
5. <Plano inteiro>: <consequência>.
6. Packshot: <produto sozinho>, the word '<NOME>' clearly readable.
Same character, same outfit and same product in every panel.
```
### Ampliar um quadro
```
The attached image is a 6-panel storyboard. Recreate ONLY panel <N> as a single full-frame, high-resolution photorealistic still. Keep its composition, camera angle, action, outfit, lighting and color grade. Do not include any other panel, grid lines or panel numbers.
```
### Quadro a partir do recorte ampliado
```
Recreate this frame as a high-resolution cinematic still. Keep the composition and action. Use the face from reference 2 and the <produto> from reference 3 exactly.
```

## 8. Personagem fictício novo (anti-morphing)
```
Create a photorealistic image of a completely new fictional adult <gênero> generated from the TWO reference individuals, using them only as subtle genetic inspiration rather than direct likeness: blend eye shape, brow geometry, nose, lip proportions, cheekbones and jawline with mild natural asymmetry, natural pores and tiny expression lines, into one cohesive person who does not strongly resemble either source. <Plano, lugar cotidiano, luz de janela>. Shot on a modern smartphone, 26mm equivalent, subtle sensor noise. Avoid morphing artifacts, feature-averaging softness, uncanny symmetry, waxy or plastic skin, face-swap look, duplicate resemblance, distorted eyes, mismatched lighting.
```
Só com rostos fictícios ou com autorização por escrito das pessoas.

## 9. Troca de rosto em cena existente
```
Replace ONLY the face and hair with the character from reference 2. Match the skin tone of the neck and hands. Keep everything else identical: clothes, pose, hands, objects, background, light and framing.
```

## 10. Reestilizar colagem
```
Fully re-render this ENTIRE image as <estilo>: <3-4 marcas do estilo>. Keep exactly the same layout, subjects, positions, colors and labels. Keep the character's <traços do DNA>. Nothing photographic may remain.
```

## 11. Adaptação de formatos (rascunho)
```
Create an AD ADAPTATION SHEET on a neutral grey board: the same ad shown in three formats side by side, each re-laid-out, not cropped: a 1:1 feed post, a 9:16 story with empty safe zones at top and bottom, a 16:9 banner with the headline on one half and the product on the other. <Textos e HEX>. Small grey labels under each. Every text spelled exactly as written, no other text.
```

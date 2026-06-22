# Prompts para Gerar Imagens — S.A Evolution Proteção Veicular

> Para gerar no ChatGPT (DALL-E). Todas as imagens devem ter estilo fotográfico realista, iluminação natural, tons quentes, visual brasileiro urbano.
> Público-alvo: pessoas de classe média/trabalhadora com carros populares de até R$50 mil (Onix, HB20, Argo, Gol, Strada, Kwid, Polo).
> Região: Curitiba-PR. Diversidade: incluir pessoas negras, pardas e brancas, homens e mulheres, 25-50 anos.

---

## 1. HERO — Imagem principal

**Proporção:** 4:3 (800×600px)  
**Uso:** Lado direito do hero, com overlay e badge sobreposto  
**Arquivo:** `hero.jpg`

```
Professional photograph, realistic style, warm natural lighting. A happy Brazilian couple (mixed race, 30s) standing next to a white Chevrolet Onix hatchback parked on a tree-lined residential street in Curitiba, Brazil. The woman is holding car keys, both smiling naturally at each other. Background shows a typical Brazilian middle-class neighborhood with apartment buildings. Golden hour lighting, shallow depth of field on the people. No text, no logos. Aspect ratio 4:3.
```

---

## 2. SOBRE — Imagem principal

**Proporção:** 16:9 (700×360px)  
**Uso:** Seção "Quem somos", foto grande com overlay gradiente  
**Arquivo:** `sobre-principal.jpg`

```
Professional photograph, realistic style. A friendly Brazilian customer service representative (Black woman, early 30s, wearing a red polo shirt) sitting at a clean modern desk, talking attentively with a male client (white, 40s, casual clothing) across the table. The desk has a laptop and a few papers. Office environment is bright, modern, minimal — white walls, warm LED lighting. The interaction looks genuine and trustworthy, like a car protection consultation. No text, no logos. Aspect ratio 16:9.
```

---

## 3. SOBRE — Grid esquerda

**Proporção:** 2:1 (400×200px)  
**Uso:** Card menor no grid da seção Sobre  
**Arquivo:** `sobre-grid1.jpg`

```
Professional photograph, realistic style. Close-up of a professional handshake between two people in a casual office setting — one is a young Brazilian man (pardo, wearing a branded red polo shirt), the other is a woman client. Focus on the hands and forearms, blurred warm background. Conveys trust, deal-closing, partnership. No text, no logos. Aspect ratio 2:1.
```

---

## 4. SOBRE — Grid direita

**Proporção:** 2:1 (400×200px)  
**Uso:** Card menor no grid da seção Sobre  
**Arquivo:** `sobre-grid2.jpg`

```
Professional photograph, realistic style. A small team of 3 Brazilian customer service professionals (diverse — one Black man, one white woman, one pardo man, all in their late 20s-30s) standing together in a bright modern office, smiling confidently at the camera. They are wearing matching red polo shirts with no visible logos. Clean, minimal office background. Conveys a reliable, approachable team. No text, no logos. Aspect ratio 2:1.
```

---

## 5. PÚBLICO-ALVO — Card CTA

**Proporção:** 5:2 (600×240px)  
**Uso:** Dentro do card navy da seção "Para quem é"  
**Arquivo:** `publico-carro.jpg`

```
Professional photograph, realistic style, slightly elevated angle. A silver Hyundai HB20 sedan parked on a clean urban street in Curitiba, Brazil. The car is in excellent condition, well-lit by soft daylight. Background shows a typical Brazilian commercial area — small shops, sidewalk, a few trees. The scene feels safe, everyday, relatable. No people, no text, no logos. Aspect ratio 5:2, wide crop.
```

---

## 6. CONTATO — Foto da equipe

**Proporção:** 5:2 (500×200px)  
**Uso:** Seção de contato, ao lado dos canais  
**Arquivo:** `contato-equipe.jpg`

```
Professional photograph, realistic style. A Brazilian woman (parda, early 30s, wearing a red polo shirt) sitting at a desk with a headset on, smiling while looking at her computer screen. She is in the middle of a customer support call. The desk has a phone, a notebook, and a small potted plant. Bright, clean, modern office. The mood is warm, efficient, human. No text, no logos. Aspect ratio 5:2, wide crop.
```

---

## Diretrizes gerais para todas as imagens

- **Estilo:** Fotográfico realista (NÃO ilustração, NÃO 3D, NÃO cartoon)
- **Iluminação:** Natural, quente, diurna
- **Carros aceitos:** Chevrolet Onix, Hyundai HB20, Fiat Argo, VW Gol, Fiat Strada, Renault Kwid, VW Polo, Fiat Mobi, Toyota Yaris, Nissan Kicks
- **Carros proibidos:** BMW, Mercedes, Audi, Porsche, Land Rover, caminhonetes grandes, esportivos
- **Pessoas:** Brasileiros diversos (negros, pardos, brancos), 25-50 anos, roupas casuais ou polo vermelha (uniforme)
- **Cenário:** Urbano brasileiro (ruas, bairros residenciais, escritório simples) — NÃO mansões, NÃO cenários europeus/americanos
- **Proibido:** Texto nas imagens, logos, marcas d'água, números de placa legíveis
- **Formato de entrega:** JPG, qualidade alta, sem compressão excessiva

---

## Como aplicar no site

Após gerar as imagens, salve-as na pasta `/sa-evolution-site/` e substitua as URLs Unsplash no `index.html`:

| Imagem | Substituir src por |
|--------|-------------------|
| Hero | `hero.jpg` |
| Sobre principal | `sobre-principal.jpg` |
| Sobre grid 1 | `sobre-grid1.jpg` |
| Sobre grid 2 | `sobre-grid2.jpg` |
| Público-alvo | `publico-carro.jpg` |
| Contato | `contato-equipe.jpg` |

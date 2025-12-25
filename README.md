# 🎄 Merry Christmas✨

Um mini “cartão de Natal” em **HTML + CSS + JavaScript**, com **neve animada**, **texto dourado com shimmer**, **animação de entrada** (“Merry Christmas” → “Nikolinha”) e **música natalina direto da web** (com controle via menu ☰).  
Depois da animação, fica **somente a imagem de fundo (clean)** — e a neve pode continuar ❄️

---

## ✨ Preview do que acontece

1. **Merry Christmas** aparece com uma animação suave  
2. **Nikolinha** aparece logo em seguida  
3. Os textos somem e fica **só a foto** (clean)  
4. **Neve continua** caindo (opcional / já vem ligada)

---

## 📁 Estrutura do projeto

/
├─ index.html
└─ bg.jpeg


Copiar código

✅ Apenas isso.

---

## 🖼️ Como usar

1. Coloque o arquivo `index.html` e a sua imagem na mesma pasta.
2. Renomeie sua imagem para **`bg.jpeg`**
3. Abra o `index.html` no navegador (celular ou PC).

> Dica: no iPhone/Android, a música **não toca automaticamente**. Você precisa tocar em **Play** no menu ☰ (por regra do navegador).

---

## 🎶 Música natalina

A música é carregada **direto da web** (Wikimedia Commons).  
Você controla no menu ☰:
- ▶️ Play / ⏸ Pause
- 🔊 Volume

---

## ☰ Controles (Menu Hambúrguer)

O projeto é pensado pra ficar **bem clean**. Por isso, os controles ficam escondidos no menu ☰:

- 🎶 **Play/Pause**
- ✨ **Sparkle** (brilho suave ao toque)
- ❄️ **More snow**
- 🔁 **Replay** (rever a animação)

---

## 🛠️ Personalização rápida

### Trocar o nome
No `index.html`, procure:
```html
<p class="line" id="name">Nikolinha</p>
e troque o texto.

Trocar o fundo
Basta substituir o arquivo bg.jpeg por outra imagem (mantendo o mesmo nome).

Trocar mensagem final
Procure:

html

<div class="smallHint">Wishing you a magical Christmas ✨</div>
✅ Requisitos
Qualquer navegador moderno (Chrome, Safari, Edge, Firefox)

Funciona em mobile ✅ (responsivo)

❤️ Créditos
Fonte natalina: Great Vibes (Google Fonts)

Música: hospedada no Wikimedia Commons

Efeito neve: Canvas (JS)

Design: estilo clean/glass + dourado natalino ✨

🎅 Feliz Natal!
Feito com carinho 🎄✨

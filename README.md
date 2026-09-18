# Convite de Casamento — Paola Benites & Erick Ribas

Convite digital (uma página, feito para celular) do casamento de
**Paola Benites e Erick Ribas**.

- **Data:** 17 de abril de 2027 (sábado)
- **Cerimônia:** 16h
- **Local (cerimônia e recepção):** Pauletto Eventos — R. Lagoa Ibirapuera, 196-456, Morumbi, Cascavel/PR, 85818-640
- **Paleta:** branco e verde oliva
- **Música:** *Perfect* — Ed Sheeran
- **Versículo:** Isaías 41:20
- **Lista de presentes e confirmação de presença:** site do casal no Casar.com

## Arquivos

- `index.html` — o convite completo (HTML/CSS/JS, sem dependências)
- `img/` — fotos do casal e do local (veja `img/README.md`)
- `audio/perfect.mp3` — música que toca no convite

## Música

A música toca **localmente** a partir de `audio/perfect.mp3` — não depende do
YouTube. Ela começa automaticamente quando a pessoa toca na capa (esse toque é
o gesto que os celulares, inclusive o iPhone, exigem para liberar o som) e pode
ser pausada/retomada pelo botão flutuante ou pelo botão da seção *Nossa música*.

Para trocar a música, substitua o arquivo `audio/perfect.mp3` por outro MP3 com
o mesmo nome (e atualize o nome/artista no `index.html`, na seção *Nossa música*).

## Como visualizar

Abra o `index.html` no navegador — é só isso.

## Como publicar (GitHub Pages)

1. No GitHub: **Settings → Pages**
2. Em *Source*, escolha **Deploy from a branch**
3. Branch: `main` · pasta: `/ (root)` → **Save**
4. Em alguns minutos o convite fica no ar em
   `https://<seu-usuario>.github.io/convite-paola-erick/`

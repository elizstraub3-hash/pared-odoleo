# Mini Paredão do Léo — mini-site

Mini-site (estilo link na bio) com fundo **preto e vermelho**, logo e música,
no mesmo modelo do site da Brook'Saints.

## Como abrir
Abra o arquivo `index.html` no navegador (ou publique a pasta em qualquer
hospedagem estática: GitHub Pages, Netlify, Vercel, etc.).

## O que já está pronto
- ✅ Layout preto e vermelho
- ✅ Player de música com o áudio enviado (`assets/musica.mp3`)
- ✅ Barra promocional animada
- ✅ Estrutura de contatos, grupos, Instagram, horário e localização
- ✅ Rodapé com crédito à Elizandra Straub

## O que falta preencher (quando o cliente enviar)
Todos os pontos marcados no site com a etiqueta vermelha **"preencher"**.
No arquivo `index.html` procure por `SEUNUMERO`, `SEUINSTA` e as tags
`placeholder-tag`:

| Campo | Onde alterar |
|-------|--------------|
| Nº do WhatsApp | `href="https://wa.me/55SEUNUMERO"` |
| Link do grupo do WhatsApp | `href="#"` no botão "Grupo do WhatsApp" |
| Instagram | `href="https://instagram.com/SEUINSTA"` |
| Horário de atendimento | seção **Funcionamento** |
| Endereço | seção **Localização** |
| Mapa | trocar o `src` do `<iframe>` pelo endereço real |

## Logo e fundo
- Logo: `assets/logo.png` (fundo já deixado transparente)
- Padrão de fundo: `assets/fundo.png`

Pra trocar qualquer um, basta substituir o arquivo mantendo o mesmo nome.

## Música
A música já está em `assets/musica.mp3`. Por regra dos navegadores, ela não
toca sozinha ao abrir — o visitante toca no botão ▶ do player.

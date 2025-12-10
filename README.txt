# Redirect Telegram — @aninhacerejinhabot?start=go

Este pacote contém uma página de redirecionamento otimizada para abrir o bot @aninhacerejinhabot com parâmetro `?start=go` automaticamente.

Como usar:
1. Suba o arquivo `index.html` no seu host (Netlify/Hostinger/etc).
2. A página tenta abrir automaticamente o app do Telegram via `tg://resolve?domain=aninhacerejinhabot&start=go`.
3. Se o app não abrir, há fallback para `https://t.me/aninhacerejinhabot?start=go`.

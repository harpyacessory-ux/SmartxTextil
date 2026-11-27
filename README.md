# Smartx — LP RFID para indústria têxtil

Landing page da campanha Google Ads **04 "Têxtil"** da Smartx (palavra-chave principal: *rfid para indústria têxtil*).

URL final prevista: `https://lp.smartx.com.br/rfid-industria-textil` (o `vercel.json` já serve a página nesse caminho e na raiz).

## Estrutura

- `index.html` — página única, autocontida (HTML + CSS + JS inline). Dependência externa: Google Fonts (Sora + Inter).
- `assets/` — imagens em WebP (fotos de produto e logos de clientes vindos do site smartx.com.br).
- `vercel.json` — hospedagem estática na Vercel.

## Decisões do cliente

- Sem menu, sem botão flutuante de WhatsApp e sem formulário próprio.
- A conversão entra pelo **shortcode do plugin** no bloco `#contato` — procure `SHORTCODE` no `index.html`.
- Números liberados: 500+ clientes, 10M+ tags, 99,9% de precisão. Payback e demais números da página têxtil do site ficam fora.

## Pendências

- Shortcode/embed do formulário.
- ID do Google Tag Manager.
- Hex oficiais da marca (hoje: preto `#141414` + amarelo `#F6B21B`, tirados do logo).
- Fotos reais: tag pendurada, impressão/codificação, mesa de conferência (bancada), tela do sistema.

## Rodar localmente

```bash
npx serve .
```

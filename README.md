# Notas PWA — protótipo para iPhone

Protótipo estático inspirado nas capturas fornecidas, preparado para GitHub Pages.

## Arquivos

- `index.html` — estrutura da tela.
- `styles.css` — interface escura, controles e Liquid Glass simulado.
- `app.js` — gera as 10.000 palavras e atualiza o horário.
- `words.txt` — lista exata das 10.000 palavras exibidas, uma por linha.
- `manifest.json`, `sw.js`, `icon.svg` — instalação como PWA e cache offline.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie **todos os arquivos desta pasta para a raiz** do repositório.
3. Abra `Settings > Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`, a branch `main` e a pasta `/ (root)`.
5. Abra o endereço gerado no Safari do iPhone.
6. Para instalar: `Compartilhar > Adicionar à Tela de Início`.

O PWA precisa ser aberto por HTTPS para o service worker e o modo offline funcionarem. O GitHub Pages já fornece HTTPS.

## Observações

A interface simula a aparência do Notas em modo escuro e o efeito Liquid Glass. O horário é atualizado automaticamente. O texto é editável, mas a lista original volta quando a página é recarregada.

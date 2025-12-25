# Art — Exibição de arte urbana

Página estática e responsiva para exibir fotografias e obras de arte urbana.

Desktop:
[Desktop banner](./screenshots/desktop.png)

Mobile:

[Desktop banner](./screenshots/mobile.png)


## Resumo
- Versão estática: HTML, CSS e Bootstrap.
- Responsivo para desktop e mobile.

## O que foi usado
- HTML5
- CSS3 (css/style.css)
- Bootstrap 5 (CDN)
- Bootstrap Icons (CDN)

## Estrutura
```
css/
  └─ style.css
img/
  ├─ art_logo.svg
  ├─ favicon.ico
  ├─ g_1.jpg
  ├─ g_2.jpg
  ├─ g_3.jpg
  ├─ g_4.jpg
  ├─ g_5.jpg
  └─ g_6.jpg
screenshots/
  ├─ desktop.png
  └─ mobile.png
index.html
LICENSE
README.md
```


## Como executar (Node)
Clone:
```bash
git clone https://github.com/Rodrigopcosta/Galeria-de-fotos-com-Bootstrap.git
```

Acesse a pasta:
```bash
cd Galeria-de-fotos-com-Bootstrap
```

Executar com npx (recomendado, sem instalação global):
```bash
npx http-server ./ -p 3000
```

Alternativa (instalar localmente e rodar via npm):
```bash
npm install --save-dev http-server
```

Adicionar script em package.json:
```json
"scripts": { "start": "http-server ./ -p 3000" }
```

Rodar:
```bash
npm start
```

## Autor
Rodrigo Costa

## Licença
MIT — arquivo LICENSE incluso.
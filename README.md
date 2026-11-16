# Site Gustavo Woci

Portfólio de Gustavo Woci — designer gráfico e web designer, Blumenau/SC.
Sites e landing pages sob medida, do primeiro papo até o site no ar.

## Estrutura

| Arquivo | O que é |
| --- | --- |
| `index.html` | Site em português |
| `en.html` | Site em inglês |
| `favicon.svg` | Símbolo da marca |

Cada página é um arquivo único: HTML, CSS e JavaScript no mesmo lugar, sem
build e sem dependência. As imagens estão embutidas em base64, então basta
abrir o arquivo no navegador ou servir a pasta estática.

## Como rodar

```bash
python3 -m http.server 8000
```

Depois é só abrir <http://localhost:8000>.

## Publicação

Qualquer hospedagem estática serve — GitHub Pages, Vercel, Netlify ou
Cloudflare Pages. Não há etapa de build.

## Licença

Código e conteúdo de autoria de Gustavo Woci. Todos os direitos reservados.

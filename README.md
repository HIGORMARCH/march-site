# march-site

Site institucional da March Contabilidade — HTML estático.

## Deploy

Hospedado no **Azure Static Web Apps** (plano Free), com deploy automático a
cada push em `main` via GitHub Actions.

URL de produção: (a definir após deploy)  
Domínio final: `marchcontabilidade.com.br`

## Estrutura

```
index.html          Página principal
404.html            Página de erro 404
robots.txt          Regras pra motores de busca
sitemap.xml         Mapa do site
assets/             Imagens, marca, CSS e JS
├── marca/          Logotipos e ícones
└── ...
```

## Rodar localmente

Não precisa build. Abra `index.html` no navegador ou sirva qualquer HTTP
estático:

```bash
python -m http.server 8080
```

Depois abra http://localhost:8080.

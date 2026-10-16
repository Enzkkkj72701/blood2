# BLOODx

Site estático (HTML + CSS + JS puro) do Pack do NunesX e das edições sob encomenda. As vendas são feitas pelo Discord.

## Estrutura

```
index.html      página única
favicon.svg     ícone da aba
vercel.json     configuração da Vercel
images/         fundo, imagem do pack e antes/depois da qualidade
```

Não precisa de build, nem de `npm install`.

## Ver no seu computador

Abra o `index.html` no navegador, ou rode um servidor local:

```
python3 -m http.server 8000
```

e acesse http://localhost:8000

## Publicar

1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel, clique em **Add New → Project** e importe o repositório.
3. Em *Framework Preset* deixe **Other**. Deixe *Build Command* e *Output Directory* vazios.
4. Clique em **Deploy**.

A partir daí, todo `git push` na branch `main` publica uma nova versão sozinho.

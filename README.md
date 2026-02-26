# Resenhas PDS

Resenhas sobre artigos de Engenharia de Software discutidos em Projeto de Software na PUC Minas.

🌐 **Site:** https://bernardogomes25.github.io/Resenhas_PDS

---

## Como adicionar uma nova resenha

1. Crie um arquivo `.md` na pasta `_posts/` com o nome no formato:
   ```
   AAAA-MM-DD-titulo-do-artigo.md
   ```
   Exemplo: `_posts/2026-03-10-design-patterns.md`

2. Adicione o cabeçalho (*front matter*) no início do arquivo:
   ```yaml
   ---
   title: "Título da Resenha"
   date: 2026-03-10
   author: Seu Nome
   source: https://link-para-o-artigo-original.com
   ---
   ```

3. Escreva a resenha em Markdown abaixo do cabeçalho.

4. Faça *commit* e *push* para o GitHub. O site será atualizado automaticamente via GitHub Pages.

---

## Estrutura do projeto

```
_posts/          ← suas resenhas ficam aqui
_layouts/        ← templates HTML (não precisa editar)
assets/css/      ← estilos (não precisa editar)
_config.yml      ← configuração do site
index.html       ← página inicial (lista de resenhas)
```

## Publicação

O site usa **Jekyll + GitHub Pages**. Qualquer push para a branch principal atualiza o site automaticamente — não é necessário instalar nada localmente.

# Template Automatizado — Solicitação de Design e Vídeo (Discord)

Site estático para gerar Markdown padronizado das demandas de Design/Vídeo.  
Basta abrir `index.html` no navegador.

## Deploy no GitHub Pages (Projeto)

1. Crie um repositório: **design-demand-template** (ou o nome que preferir).
2. Faça commit destes arquivos na branch `main`.
3. Vá em **Settings → Pages** e em *Source* selecione **Deploy from a Branch**: `main` + `/ (root)`.
4. O GitHub Pages publicará algo como: `https://<org-ou-user>.github.io/<repo>/`.

> Dica: para URL própria, crie um arquivo `CNAME` na raiz com o domínio e aponte o DNS para o Pages.

## Modo Usuário/Organização (Root)
Se quiser usar como site principal, crie um repositório chamado **<seu-usuario>.github.io** e coloque o `index.html` na raiz.

## Observações
- GitHub Pages é **público**. Para restringir a membros, use algo como **Cloudflare Access**, Netlify com **Identity**, ou hospede atrás de SSO.
- O app é client-side e não requer build. Não há dependências externas.

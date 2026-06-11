# synetiqlab-site

Landing da marca-mãe **Synetiq Lab** (`synetiqlab.com`).

- Site estático de uma página (`index.html`), sem build.
- Fundo de rede neural interativo (canvas), com salvaguardas de performance (menos nós no mobile, respeita `prefers-reduced-motion`, pausa em aba oculta).
- CTA → `https://footballmind.synetiqlab.com` (o produto #1).

## Deploy (Cloudflare Pages, via git)
- Cloudflare → Workers & Pages → Create → Pages → **Connect to Git** → este repo.
- Framework preset: **None** · Build command: *(vazio)* · Output directory: **`/`** (raiz).
- Custom domains: `synetiqlab.com` + `www`.

Atualizar a página = editar `index.html` e `git push` (deploy automático).

# Guia de assinatura — Ponto e Holerite (Grupo Tomaz)

Página única, sem dependências: todo o conteúdo e todas as imagens estão dentro do
`index.html`. Basta servir o arquivo em qualquer lugar.

## Publicar no GitHub Pages

1. Crie um repositório chamado **`guia-ponto`** na conta **`JoaCalistormrp`**
   (github.com → New repository). Pode ser público.
2. Em **Add file → Upload files**, arraste os três arquivos desta pasta:
   `index.html`, `robots.txt` e `.nojekyll`.
   > O `.nojekyll` começa com ponto e fica oculto no Finder/Explorer.
   > No Windows: Exibir → Itens ocultos. No macOS: `Cmd + Shift + .`
3. **Commit changes**.
4. Vá em **Settings → Pages** e configure:
   - Source: **Deploy from a branch**
   - Branch: **main** / pasta **/ (root)** → **Save**
5. Aguarde 1 a 2 minutos. O endereço final será:

   **https://joacalistormrp.github.io/guia-ponto/**

Esse é o endereço que o QR do cartaz aponta. Se você usar outro nome de
repositório ou outra conta, o QR precisa ser gerado de novo.

## Sobre a privacidade

O site do GitHub Pages é público — qualquer pessoa com o link abre, sem login.
Por isso a página já vai com:

- `<meta name="robots" content="noindex, nofollow, noarchive, nosnippet, noimageindex">`
- `robots.txt` bloqueando todos os buscadores

Isso mantém a página fora do Google. Não é um controle de acesso: quem receber o
link consegue abrir. As telas já estão com os nomes tarjados e os valores do
holerite rasurados.

## Atualizar depois

Suba um `index.html` novo por cima (Upload files → commit). A publicação leva
cerca de um minuto e o link continua o mesmo — o cartaz impresso não precisa ser
trocado.

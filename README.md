# Site Sabiah English School

Site estático: `index.html` + `favicon.svg`. Não precisa de build nem de instalação.

## Como publicar (escolha uma)

- **Netlify:** acesse app.netlify.com/drop e arraste a pasta `sabiah-site`.
- **Cloudflare Pages:** Workers & Pages > Create > Pages > Upload assets, envie a pasta.
- **Vercel:** `npx vercel` dentro da pasta, ou importe o repositório.
- **GitHub Pages:** suba os arquivos para um repositório, depois Settings > Pages > Deploy from a branch.

Para usar um domínio próprio, aponte o domínio nas configurações da plataforma escolhida.

## O que editar

Tudo está em `index.html`:

- WhatsApp: procure por `5547988883216` (links) e `(47) 98888-3216` (texto).
- E-mail: procure por `sabiahenglishschool@gmail.com`.
- Instagram: `sabiah.es` e `sabiah.dev`.
- Link do canal Kids no YouTube: ainda não existe no site. Adicione um `<a class="btn ghost" href="...">` ao lado do botão da seção `id="kids"`.
- Cores: bloco `:root` no início do `<style>`.

As fontes (Poppins e DM Sans) carregam do Google Fonts, então o site precisa de internet para exibi-las.

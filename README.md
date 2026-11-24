# Assinaturas de e-mail Pratika

Ferramenta para gerar as assinaturas de e-mail da equipe Pratika Contabilidade, com os ícones de Instagram, LinkedIn e WhatsApp clicáveis. O mesmo site também hospeda as imagens da assinatura.

## O que tem aqui

| Arquivo | Para que serve |
|---|---|
| `index.html` | O gerador de assinaturas |
| `config.js` | Links padrão do Instagram, LinkedIn e WhatsApp (opcional) |
| `img/` | Logo e ícones usados nas assinaturas |

## 1. Links da empresa (opcional agora)

Os links do Instagram, do LinkedIn e do WhatsApp da empresa podem ser preenchidos **na própria página**, em "Links da empresa". O navegador de quem preencher guarda esses links.

Se quiser que os links já venham preenchidos para todo mundo, edite o `config.js` (no GitHub: abra o arquivo → ícone de lápis → preencha → **Commit changes**). Em cerca de 1 minuto o site se atualiza sozinho.

## 2. Subir para o GitHub

1. Crie uma conta em github.com, se ainda não tiver.
2. Clique em **New repository**, dê o nome `assinaturas-pratika` e crie o repositório.
3. Na página do repositório, clique em **uploading an existing file** e arraste todos os arquivos desta pasta, incluindo a pasta `img`.
4. Clique em **Commit changes**.

## 3. Publicar de graça no Cloudflare Pages

1. Crie uma conta em dash.cloudflare.com.
2. Vá em **Workers & Pages → Create → Pages → Connect to Git** e escolha o repositório `assinaturas-pratika`.
3. Em *Build settings*, deixe o comando de build vazio e use `/` como pasta de saída.
4. Clique em **Save and Deploy**. O site fica em `https://assinaturas-pratika.pages.dev` (ou um nome parecido).

Opcional: em **Custom domains** você pode usar, por exemplo, `assinaturas.pratikacontabilidade.com.br`. Se usar, coloque esse endereço em `enderecoSite` no `config.js`.

> Alternativa: GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## 4. Usar

1. Abra o site, preencha nome, cargo e telefone.
2. Clique em **Copiar assinatura**.
3. Cole em Gmail (Configurações → Ver todas as configurações → Assinatura) ou Outlook (Configurações → Email → Assinaturas).
4. Envie um e-mail de teste e toque em cada ícone.

## Atenção

- **Não apague nem renomeie os arquivos da pasta `img`** depois que as assinaturas estiverem em uso. Todas as assinaturas já enviadas buscam as imagens nesse endereço.
- Para trocar a logo no futuro, substitua o arquivo mantendo o mesmo nome. Alguns programas de e-mail podem demorar para mostrar a versão nova.
- Alterações nos links só valem para as assinaturas geradas depois. As já instaladas precisam ser copiadas e coladas de novo.

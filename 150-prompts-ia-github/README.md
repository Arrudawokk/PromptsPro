# Página de vendas 150 Prompts Más Utilizados con IA

Este pacote contém a versão atual da página de vendas em espanhol, com a foto do produto e todos os 7 botões conectados ao checkout:

https://pay.hotmart.com/P107753901N

## Arquivos

- `index.html`: página completa, estilos, FAQ e eventos de analytics.
- `assets/`: duas versões otimizadas da foto do produto em WebP.

A página é estática. Não precisa instalar dependências nem executar uma etapa de build.

## Como subir ao GitHub

1. Extraia o ZIP no computador.
2. Crie ou escolha um repositório no GitHub.
3. Envie o conteúdo extraído para a raiz do repositório: `index.html`, `assets/` e este README.
4. Preserve os nomes dos arquivos e a estrutura da pasta `assets`.
5. Salve os arquivos em um commit.

Envie os arquivos extraídos, não apenas o arquivo ZIP. Para testar no computador, abra `index.html` no navegador.

## Hospedagem

Use o repositório como fonte para uma hospedagem de sites estáticos que permita uso comercial. Se houver configurações de publicação, a pasta pública é a raiz do projeto e não há comando de build.

O GitHub Pages restringe o uso para sites direcionados principalmente a facilitar transações comerciais. Por isso, ele não é indicado como hospedagem desta página de vendas. O código pode ficar no repositório do GitHub e ser publicado em outro serviço.

Fonte: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits

## Campos ainda pendentes

Os botões e a foto estão configurados. A página ainda mantém os seguintes marcadores, porque os dados correspondentes não foram informados:

- `[FORMATO_DEL_ARCHIVO]`
- `[MÉTODO_DE_ENTREGA]`
- `[URL_TERMINOS]`
- `[URL_PRIVACIDAD]`
- `[URL_REEMBOLSO]`
- `[URL_SOPORTE]`

Substitua esses campos em `index.html` pelos dados reais do produto.

Os eventos `view_offer`, `click_checkout` e `view_faq` são enviados para `window.dataLayer`. Nenhum ID de analytics ou pixel foi inserido.

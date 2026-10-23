# Site de apresentação do Excia ERP

Site estático e responsivo, sem bibliotecas externas. O player incorpora o vídeo do YouTube quando `videoUrl` recebe um link do YouTube. Pode ser publicado gratuitamente no GitHub Pages. A identidade visual foi ajustada com base no site oficial da Excia: destaque laranja, preto/cinza, fundo claro e tipografia sem serifa de sistema.

## Antes de publicar

Edite `index.html` e, no objeto `siteConfig` ao final do arquivo:

1. O player está configurado para incorporar o vídeo `https://youtu.be/hNFlXUB_Yiw`. Para trocar o vídeo, atualize `videoUrl`. Também é aceita uma URL direta HTTPS de arquivo MP4 ou WebM.
2. Substitua os valores vazios `url` dos recursos pelos endereços oficiais.
3. Confirme se os textos da página estão aprovados.

URLs vazias aparecem como “Link oficial ainda não informado” e não são clicáveis.

## Pendências editoriais do roteiro recebido

- No tópico 06, “Este é um recurso opções” parece conter erro de redação; a frase e a pontuação precisam de revisão.
- A seção de tópicos foi removida a pedido. O trecho do tópico 09 que chegou na conversa de referência estava truncado em “barra hori”; não foi completado nem publicado.
- O erro editorial no tópico 06 permanece registrado aqui para revisão, mas o roteiro não é exibido no site.
- Marcas de tempo, legendas, logotipo e identidade visual oficial não foram fornecidos e não foram inventados.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos desta pasta para a raiz do repositório.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch principal e a pasta **/(root)**, depois salve.
5. Aguarde a publicação e use o endereço apresentado pelo GitHub Pages para compartilhar a página.

O caminho dos menus do GitHub pode mudar. Para atualizar, edite `index.html` no próprio GitHub ou envie uma versão nova dos arquivos.

## Observações

- A página não inclui analytics, cookies, formulários ou trackers.
- A página incorpora o vídeo pelo player sem cookies do YouTube. Uma URL direta para MP4/WebM usa o player nativo do navegador.
- O arquivo MP4 local tem cerca de 154 MB; não o envie ao repositório Git comum (o GitHub bloqueia arquivos acima de 100 MiB, e Git LFS não é compatível com Pages). O vídeo do YouTube configurado evita esse limite.
- Analytics, domínio próprio e serviços pagos não estão configurados.


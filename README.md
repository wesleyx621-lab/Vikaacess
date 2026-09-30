# ViKa acessórios

Site bio estático, leve e responsivo. Inclui todas as imagens; não precisa instalar dependências, usar npm ou configurar variáveis de ambiente.

## Publicar pelo GitHub e Netlify

1. Extraia o ZIP no computador.
2. Crie um repositório no GitHub, por exemplo `vika-acessorios`.
3. Envie o CONTEÚDO da pasta extraída: `site/`, `netlify.toml` e este `README.md`. Não envie apenas o ZIP. O arquivo `netlify.toml` deve ficar na raiz do repositório.
4. Na Netlify, importe um projeto existente do GitHub e escolha esse repositório.
5. Se forem solicitadas configurações:
   - Framework: nenhum / Other.
   - Base directory: deixe vazio.
   - Build command: deixe vazio.
   - Publish directory: `site`.
   - Variáveis de ambiente: nenhuma.
6. Publique e aguarde a Netlify fornecer o endereço do site. Esse é o link para colocar na bio do Instagram.

O arquivo `netlify.toml` já define a pasta de publicação.

## Alternativa: publicação manual

Na área de publicação manual da Netlify, arraste a pasta `site`, que contém `index.html` e a pasta `assets`.

## Editar

- Textos, links, cores e estilos: `site/index.html`.
- Imagens: `site/assets/`.
- WhatsApp configurado: https://w.app/codsoq
- Instagram configurado: https://www.instagram.com/vika_acess/

Para visualizar localmente, abra `site/index.html` no navegador. O recurso de compartilhar/copiar link deve ser usado no endereço publicado.

Documentação oficial da configuração Netlify:
https://docs.netlify.com/build/configure-builds/file-based-configuration/

# PATO — protótipo da landing page

Página estática em português de Portugal, inspirada diretamente na identidade visual do PDF. Inclui apresentação do campo, programa ilustrativo com separadores manhã/tarde/noite, perguntas frequentes e contactos.

## Abrir

Abrir `site/dist/index.html` no navegador. O protótipo também funciona sem ligação à Internet: imagens, fontes e interações são locais.

Durante esta sessão, a pré-visualização está disponível em http://127.0.0.1:4174/ . É um endereço local, acessível neste computador, não uma publicação online.

## Alterar os conteúdos

- Textos, perguntas, contactos e referências às imagens: `site/dist/index.html`.
- Cores, composição e versões para telemóvel: `site/dist/styles.css`.
- Menu móvel e separadores do programa: `site/dist/app.js`.
- Fotografias e ilustrações usadas na página: `site/dist/assets/`.
- Tipografia alojada localmente: `site/dist/fonts/`.

As cinco cores da identidade estão no início do CSS. Usam-se Anton e Schoolbell do PDF; o logótipo original preserva a tipografia Aloja. DM Sans complementa os textos de leitura.

## Conteúdo provisório

Os textos e o programa são propostas para o protótipo, a validar pela organização. Datas, local e preço estão por anunciar. Não existe formulário de inscrição nem recolha de dados. Os botões de contacto abrem o email ou o Instagram indicados no PDF; não enviam mensagens automaticamente.

Os logótipos, patos e fotografias foram extraídos do PDF fornecido. Os originais extraídos ficam em `public/assets/`; a pasta `site/dist/assets/` contém as cópias usadas pelo website.

## Partilhar os ficheiros

Enviar a pasta `site/dist` completa. O destinatário pode abrir `index.html` diretamente. Uma futura publicação pode usar qualquer alojamento de sites estáticos.

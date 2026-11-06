# Nativa — Landing page v0.4

Site estático da Nativa, usando identidade visual e renders fornecidos pelo cliente, além do texto institucional encaminhado pelo CEO.

## Executar

Abra esta pasta no VS Code e execute `index.html` via Live Server. Não é preciso instalar dependências.

## Organização

- `index.html` — conteúdo e estrutura
- `css/styles.css` — estilos e responsividade
- `js/main.js` — menu mobile e ano do rodapé
- `assets/` — logo e renders otimizados da Nativa

## Identidade visual

- Verde: `#39452F`
- Creme: `#F6EFDF`
- Dourado: `#B49264`
- Fonte secundária oficial: Montserrat, importada via Google Fonts
- Fonte principal oficial: Soage — ainda não fornecida com licença/arquivo web, portanto títulos usam Georgia como alternativa temporária.

## Atenções antes da publicação

1. **Validar telefone**: foi informado `(77) 9824-9600`, usado literalmente em todos os CTAs (`wa.me/557798249600`). Confirme se este número está correto e ativo para WhatsApp, pois aparenta ter oito dígitos locais.
2. **Projetos sem nomes oficiais**: imagens identificadas apenas por categorias descritivas, sem inventar nomes, localizações ou premiações. Confirmar se as categorias refletem cada projeto.
3. Conferir os textos adaptados e obter aprovação editorial final do cliente.
4. Substituir Georgia pela fonte Soage quando houver arquivo adequado e autorização de uso.
5. Configurar domínio, ícone, imagem de compartilhamento, analytics e demais dados de publicação quando disponíveis.
6. Confirmar condições de privacidade e eventuais requisitos legais antes de adicionar formulários ou rastreadores.

## Nota

O material do CEO posiciona a Nativa como estúdio de arquitetura e consultoria em sustentabilidade. O site usa esta descrição e mantém o logotipo original "Arquitetura e Paisagismo" sem alterá-lo.

## Alterações da v0.4

- Mensagem única e mais acolhedora nos dois links de WhatsApp.
- Numeração interna removida dos cinco cartões de Nossa Filosofia.
- Margem dos títulos dos cartões ajustada para o novo layout.
- Mantidos os demais números de navegação, serviços e processo.

## Manutenção do HTML

- `index.html`: estrutura semântica organizada por seções com comentários.
- `css/styles.css`: estilos existentes, mais correção de alinhamento `.link-with-arrow` ao final.
- `js/main.js`: menu móvel e ano automático (sem alterações).
- `assets/`: arquivos gráficos originais (sem alterações).

### Setas dos links

O SVG com classe `.link-arrow` deve estar **dentro** do elemento `<a>` com classe `link-with-arrow`.
Isso impede setas soltas no rodapé e no contato.

### Atenção

Confirme o número comercial do WhatsApp antes de enviar a versão final.

testando branch develop

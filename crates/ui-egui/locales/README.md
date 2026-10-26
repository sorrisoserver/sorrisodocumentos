# Traduções pt-BR — Sorriso Server - Documentos

Estes catálogos são a base de localização brasileira controlada pelo projeto Sorriso Server.
O build carrega `locales/pt-br/common.tsv` e `locales/pt-br/wordcraft.tsv`
deste repositório com prioridade sobre o catálogo pt-BR externo. Os demais idiomas
continuam vindo de `CRAFT_I18N_DIR` quando disponível.

## Origem e direitos

Base inicial: [ArtCraft craft-i18n](https://github.com/storytold/craft-i18n),
arquivos `locales/pt-br/common.tsv` e `locales/pt-br/wordcraft.tsv`,
consultados em 26/10/2026. Código e catálogos publicados em regime
MIT OU Apache-2.0. Direitos autorais dos autores originais preservados;
ver os arquivos `LICENSE-MIT` e `LICENSE-APACHE` do projeto e
[licenças da origem](https://github.com/storytold/craft-i18n).

## Como revisar

1. Edite apenas a terceira coluna do TSV: contexto, texto em inglês e tradução.
2. Preserve tabulações, placeholders (`{name}`), variantes plurais e reticências.
3. Acrescente as traduções de botões, tooltips, menus contextuais e diálogos.
4. Verifique o relatório `cargo xtask i18n-report`, o audit de interface
   e capturas de tela em português. Avalie truncamentos e traduções ausentes.
5. Execute `cargo xtask ci` e teste a interface no Windows antes do merge.

Os identificadores internos de comandos, fórmulas e formatos de arquivos não
devem ser traduzidos. A localização é apenas da interface e de suas mensagens.

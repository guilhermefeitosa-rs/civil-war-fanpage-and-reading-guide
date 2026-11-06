# Guerra Civil — Guia de Leitura (Civil War: Reading Guide)

Fan page independente e educacional, sem vínculo oficial com a Marvel Comics. Feita com HTML, CSS e JavaScript puros.

## Como executar
Abra `index.html` no navegador (ou use a extensão Live Server do VS Code). Não precisa de servidor nem de instalação.

## Estrutura
Cada seção é uma página HTML própria; a navegação acontece na mesma aba.
- `index.html` (Início), `historia.html`, `guia.html`, `personagens.html`, `sobre.html`
- `css/style.css`: visual de todas as páginas (paleta em variáveis no topo)
- `js/editions.js`: dados das 141 edições
- `js/script.js`: código comum (menu mobile e carregamento de imagens)
- `js/guia.js`: lista, busca, filtros, paginação e progresso (só em `guia.html`)
- `assets/images/`: imagens (`hero/`, `editions/`, `characters/`)
- `docs/`: lista original, instruções de imagens, notas de revisão e lista de nomes de imagens

O cabeçalho e o rodapé se repetem nas 5 páginas. Ao alterar um link do menu, altere nos 5 arquivos.

## Dados
- **79** entradas originais → **141** edições individuais após expandir os **25** intervalos.
- Ordem preservada exatamente. O campo `position` é a posição na leitura; `number` é o número impresso na edição.
- Descrições e observações estão vazias, para preenchimento futuro. Nenhuma data, autor ou sinopse foi inventada.
- A ordem é a lista fornecida, sem verificação bibliográfica oficial.

## Funcionalidades
Busca por série/número, filtro (todas, não lidas, concluídas), paginação de 24 itens, progresso salvo no `localStorage`, três modalidades de leitura, placeholders de imagem e menu mobile.
O progresso é calculado sobre a modalidade escolhida (no guia completo, sobre as 141 edições), ignorando busca e filtros.

## Modalidades
- Essencial: `Civil War` (5 edições, #3 a #7, pois #1 e #2 não estão na lista).
- Recomendada: seleção provisória de 30 edições (títulos "Civil War").
- Completa: 141 edições.

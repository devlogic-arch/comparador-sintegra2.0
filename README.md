📊 Comparador de Sintegra
Ferramenta desenvolvida para comparar dois arquivos Sintegra de uma mesma empresa e de um mesmo mês.
O objetivo é identificar divergências entre o arquivo gerado pela empresa e o arquivo gerado pelo usuário (no meu caso, utilizamos o software Domínio em contabilidade).

🚀 Como funciona
O usuário seleciona dois arquivos Sintegra (empresa x usuário).

A ferramenta realiza a comparação linha a linha.

São apontadas as divergências encontradas, como:

Notas faltando no arquivo 1 (ex.: nota 123 existe no arquivo 2, mas não no 1).

Notas faltando no arquivo 2.

CFOP divergente (ex.: nota no arquivo 1 com CFOP 1403 | no arquivo 2 com CFOP 1102).

Valor divergente (ex.: nota 123 com valor 12,00 no arquivo 1 | nota 123 com valor 5,00 no arquivo 2).

🛠️ Tecnologias utilizadas
HTML – interface simples para seleção dos arquivos

CSS – estilização da aplicação

JavaScript – lógica de comparação e exibição das divergências

🎯 Objetivo
Facilitar a conferência de arquivos Sintegra, garantindo maior precisão e agilidade na identificação de inconsistências fiscais.

✨ Diferencial
Esse projeto foi vibe coded por mim (projeto inspirado em outro projeto já existe com a mesma funcionalidade), com foco em resolver uma necessidade real do dia a dia da contabilidade.
A ideia é oferecer uma ferramenta prática, intuitiva e que reduza o tempo gasto em conferências manuais. 

PS: Reproduzir essa ferramenta foi um desafio pessoal.

🔧 Próximos passos
Implementar exportação das divergências em CSV/Excel.

Adicionar filtros para facilitar análise (por CFOP, valor, nota).

Criar interface mais amigável para visualização dos resultados.

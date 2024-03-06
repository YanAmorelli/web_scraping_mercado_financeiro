# Web Scraping para Mercado financeiro

Projeto voltado a prática de web scraping


## TODO
- Alterar a função get_info_acao: trocar modo de fazer request para aiohttp e adicionar import do asyncio para buscar informações de maneira assíncrona, reduzindo assim o tempo de execução
- O erro: `list index out of range` no bloco try execpt ocorre pois no site dados do mercado não tem dados de valuation dessas ações, com isso, adicionar na função get_info_acao um bloco de try except, 
caso não tenha essa informação preencher o valor como nulo para ao menos ter o valor da cotação

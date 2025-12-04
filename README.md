# Como editar o mapa

1. Atualize os profissionais que aparecem no modal editando `profissionais.json` (cada objeto precisa ter nome, endereço, cidade e estado com sigla).
2. Se quiser que o mapa use outro JSON, ajuste a constante `URL_PROFISSIONAIS` no `mapa.html` para apontar para a nova URL.
3. Para testar localmente, basta abrir `mapa.html` em um servidor ou navegador; o script já busca o JSON e preenche os estados automaticamente.

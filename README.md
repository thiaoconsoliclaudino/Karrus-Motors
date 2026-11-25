# Bavaresco Car Care

Sistema web da Bavaresco Car Care: site, app do cliente e painel do Ângelo (agenda, soluções, clientes, carros, financeiro, gráficos, equipamentos e configurações).

## Arquivos
- `index.html` — o sistema completo (HTML, CSS e JavaScript em um único arquivo).
- `cidades.json` — municípios e distritos do Brasil (IBGE), usados na busca de cidades.

## Importante
Esta versão foi feita para rodar como artifact do Claude. O login (conta Claude) e o banco de dados usam as capacidades `db` e `user` do Claude, que não existem fora dele. Aberto direto no navegador, o sistema mostra a tela "Entre com sua conta Claude".

Para produção (Lovable/Supabase), é preciso trocar essas partes por login com e-mail e senha e um banco próprio.

## Coleções do banco
`bookings` (reservas), `solutions` (soluções), `txs` (financeiro da empresa), `cars` (carros), `equip` (equipamentos), `members` (usuários), `events` (agenda), `unidades` (matriz e filiais), `feriados` (feriados cadastrados), `cfg/main` (preços, agenda, taxas, gráficos). Financeiro pessoal: `data/users/<id>` (privado por conta).

## Links diretos
`#site`, `#cliente`, `#painel` no fim do endereço.

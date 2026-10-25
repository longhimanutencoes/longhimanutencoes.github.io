# Portal do cliente · Longhi Manutenções

Página onde o cliente entra com usuário e senha e acompanha as ordens de serviço dele:
a que está em andamento, o histórico e o valor total depois de finalizada.

- `index.html`: o portal
- `config.js`: endereço e chave pública do Supabase (a mesma do app)

O acesso de cada cliente é criado no app Controle de OS
(https://leandrolonghi.github.io/caderno-servicos/), em Ajustes › Clientes e máquinas.
As funções do banco ficam em `supabase/portal.sql` no repositório do app.

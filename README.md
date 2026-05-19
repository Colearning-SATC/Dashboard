# Dashboard Colearning

Projeto preparado para hospedagem no Vercel ou GitHub Pages.

## Estrutura

- `index.html`: código principal do dashboard
- `data/dashboard_data.json`: base de dados das startups, contratos, KPIs e histórico

## Como atualizar os dados

1. Abra `data/dashboard_data.json`
2. Edite, adicione ou remova registros
3. Salve o arquivo
4. Envie para o GitHub
5. O Vercel atualizará o dashboard automaticamente após o push

## Observação

Para testar localmente, use um servidor local. Abrir o `index.html` diretamente com duplo clique pode bloquear o carregamento do JSON em alguns navegadores.

Exemplo:

```bash
python -m http.server 8000
```

Depois acesse:

```txt
http://localhost:8000
```

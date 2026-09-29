# bio-dimitriqueiroz

Páginas de "Link na Bio" hospedadas via GitHub Pages no domínio `bio.loubus.com`.

## Estrutura

- `/dimitriqueiroz/` — página do Dimitri Queiroz (acessível em `bio.loubus.com/dimitriqueiroz`)
- `index.html` (raiz) — redireciona para `/dimitriqueiroz/`
- `CNAME` — configura o domínio customizado do GitHub Pages

## Adicionando uma nova página

Crie uma nova pasta com o nome desejado (ex: `novapessoa/`) contendo um `index.html`, faça commit e push. Ela ficará disponível em `bio.loubus.com/novapessoa`.

## DNS

No provedor de DNS do domínio `loubus.com`, adicione um registro `CNAME`:

```
bio.loubus.com  ->  <seu-usuario>.github.io.
```

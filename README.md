# vallencisaude.github.io

Site principal da organização **vallencisaude** no GitHub Pages, ligado ao domínio **vallencisaude.com.br** (arquivo `CNAME`).

Cada repositório da organização aparece numa "pasta" do domínio:

| Endereço | Repositório |
|---|---|
| `vallencisaude.com.br/salas/` | [`salas`](https://github.com/vallencisaude/salas): salas para profissionais da saúde |
| `vallencisaude.com.br/` | este repositório |

**Enquanto o site principal da clínica não existe**, `index.html` e `404.html` levam para `/salas/`, mantendo os parâmetros do link (UTM). Quando o site principal for feito, ele entra aqui no lugar desses dois arquivos; `/salas/` continua funcionando.

`robots.txt` libera o site para os buscadores e aponta o sitemap das salas.

## DNS (Registro.br)

| Tipo | Nome | Dados |
|---|---|---|
| A | vallencisaude.com.br | 185.199.108.153 |
| A | vallencisaude.com.br | 185.199.109.153 |
| A | vallencisaude.com.br | 185.199.110.153 |
| A | vallencisaude.com.br | 185.199.111.153 |
| CNAME | www.vallencisaude.com.br | vallencisaude.github.io |

O `www` é redirecionado pelo GitHub para o endereço sem `www`.

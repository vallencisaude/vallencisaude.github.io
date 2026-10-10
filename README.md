# vallencisaude.github.io

Site principal da organização **vallencisaude** no GitHub Pages, ligado ao domínio **vallencisaude.com.br** (arquivo `CNAME`).

Cada repositório da organização aparece numa "pasta" do domínio:

| Endereço | Repositório |
|---|---|
| `vallencisaude.com.br/salas/` | [`salas`](https://github.com/vallencisaude/salas): salas para profissionais da saúde |
| `vallencisaude.com.br/` | este repositório: agrupador de links (link da bio do Instagram) |

## Agrupador de links (`index.html`)

Página principal do domínio, com o topo da clínica e 4 botões. Para trocar um destino, mude só o `href` do botão no `index.html`.

| Botão | Destino atual |
|---|---|
| Consultas e Exames | WhatsApp Pacientes, (79) 99941-3951 (até o site de pacientes ficar pronto) |
| Nossas Salas e Espaços | `/salas/`, repassando os parâmetros do link (UTM, gclid, fbclid) |
| Nossa Localização | Google Maps (trocar pelo Perfil da Empresa no Google quando chegar) |
| Quer fazer uma Parceria? | Formulário atual do Google (até a página `/parcerias` ficar pronta; as respostas vão para o WhatsApp Profissionais) |

As imagens ficam em `assets/agrupador/`, incluindo a prévia de compartilhamento (`compartilhar.jpg`, 1200 × 630).

`404.html` leva qualquer endereço inexistente fora de `/salas/` para a página principal, mantendo os parâmetros do link. `robots.txt` libera o site para os buscadores e aponta os sitemaps da raiz e das salas.

## DNS (Registro.br)

| Tipo | Nome | Dados |
|---|---|---|
| A | vallencisaude.com.br | 185.199.108.153 |
| A | vallencisaude.com.br | 185.199.109.153 |
| A | vallencisaude.com.br | 185.199.110.153 |
| A | vallencisaude.com.br | 185.199.111.153 |
| CNAME | www.vallencisaude.com.br | vallencisaude.github.io |

O `www` é redirecionado pelo GitHub para o endereço sem `www`.

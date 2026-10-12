# vallencisaude.github.io

Site principal da organização **vallencisaude** no GitHub Pages, ligado ao domínio **vallencisaude.com.br** (arquivo `CNAME`).

Cada repositório da organização aparece numa "pasta" do domínio:

| Endereço | Repositório |
|---|---|
| `vallencisaude.com.br/salas/` | [`salas`](https://github.com/vallencisaude/salas): salas para profissionais da saúde |
| `vallencisaude.com.br/` | este repositório: agrupador de links (link da bio do Instagram) |
| `vallencisaude.com.br/parcerias/` | este repositório (pasta `parcerias/`): formulário de parcerias |

## Agrupador de links (`index.html`)

Página principal do domínio, com o topo da clínica e 4 botões. Para trocar um destino, mude só o `href` do botão no `index.html`.

| Botão | Destino atual |
|---|---|
| Consultas e Exames | WhatsApp Pacientes, (79) 99941-3951 (até o site de pacientes ficar pronto) |
| Nossas Salas e Espaços | `/salas/`, repassando os parâmetros do link (UTM, gclid, fbclid) |
| Nossa Localização | Google Maps (trocar pelo Perfil da Empresa no Google quando chegar) |
| Quer fazer uma Parceria? | `/parcerias/` |

As imagens ficam em `assets/agrupador/`, incluindo a prévia de compartilhamento (`compartilhar.jpg`, 1200 × 630).

## Parcerias (`parcerias/index.html`)

Formulário com as 10 perguntas do documento "Formulario_Parcerias_VALLENCI" (todas obrigatórias; na 06 dá para marcar mais de uma opção). Ao enviar, o site abre o **WhatsApp Profissionais, (79) 99647-4061**, com as respostas já organizadas na mensagem, e mostra uma confirmação com o link de novo. O site não guarda as respostas.

- Número do WhatsApp: atributo `data-whatsapp` do `<form>`.
- Logos dos parceiros: lista "Marcas que já são parceiras", com os arquivos em `assets/parceiros/`. São os mesmos do site das salas: ao incluir ou tirar um parceiro, atualize os dois.
- Prévia de compartilhamento: `assets/parcerias/compartilhar.jpg`.

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

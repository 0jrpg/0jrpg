<div align="center">

<img src="assets/header.svg" alt="0jrpg" width="100%"/>

<a href="https://github.com/0jrpg"><img src="https://img.shields.io/badge/GitHub-0jrpg-0b1020?style=for-the-badge&logo=github&logoColor=7dd3fc" alt="GitHub"/></a>
<a href="https://github.com/alphalanguage/alf"><img src="https://img.shields.io/badge/Alpha-.alf-05261c?style=for-the-badge&logoColor=6ee7b7" alt="Alpha Language"/></a>
<a href="https://educaturdi.vercel.app"><img src="https://img.shields.io/badge/EducaTurdi-online-0d2552?style=for-the-badge&logo=vercel&logoColor=fde68a" alt="EducaTurdi"/></a>
<img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>

<img src="assets/terminal.svg" alt="terminal" width="100%"/>

</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## ⭐ em destaque

<div align="center">

<a href="https://github.com/EducaTurdi/EDUTRD"><img src="assets/card-educaturdi.svg" alt="EducaTurdi, plataforma escolar" width="100%"/></a>

<br>

<a href="https://github.com/alphalanguage/alf"><img src="assets/card-alf.svg" alt="Alpha Language, linguagem de programação em português" width="100%"/></a>

</div>

<details>
<summary><b>🎓 EducaTurdi: o que é</b></summary>
<br>

Plataforma escolar moderna e integrada, feita em **Next.js + TypeScript**, com **Supabase (PostgreSQL)** no banco e deploy na **Vercel**. Tem identidade visual própria, microanimações e transições suaves, pra fugir do jeito dos sistemas escolares tradicionais. O foco é dar mais organização, praticidade, modernidade e conexão pra comunidade escolar.

📧 Quer um sistema assim pra sua escola? **EducaTurdi@gmail.com**

</details>

<details>
<summary><b>🇧🇷 Alpha Language: o que é</b></summary>
<br>

Uma linguagem brasileira que transforma arquivos `.alf` em aplicações web completas. Você escreve HTML, JS e Python num só código, em português, e o `tradutor.py` gera o `.html` pra você.

```
<janela> #B0C4DE {login}
*usuario "Usuário"
*senha "Senha"
@entrar
&mensagem "Bem-vindo ao Alpha"
</janela>
```

**Como rodar:** instale a dependência uma vez (`py -m pip install requests`), abra o `tradutor.py`, informe o nome do `.alf` e depois o nome do `.html` de saída (sem a extensão). O `dicionario.md` explica cada comando.

</details>

<img src="assets/divider.svg" width="100%" alt=""/>

## 🧭 com o que eu programo

Clica em cada bloco pra abrir 👇

<details>
<summary><b>🌐 Aplicações web com Next.js + TypeScript</b></summary>
<br>

Meu dia a dia é **Next.js (App Router)** com **TypeScript**: páginas, rotas, componentes e tipos. É a base do EducaTurdi, do site de arquivos e do blog névoa.

</details>

<details>
<summary><b>🗄️ Banco de dados com Supabase + PostgreSQL</b></summary>
<br>

No EducaTurdi uso **Supabase** em cima de **PostgreSQL** pros dados da plataforma escolar. Em outros projetos prefiro nem ter banco: o próprio GitHub guarda o conteúdo.

</details>

<details>
<summary><b>🔤 Linguagem de programação própria</b></summary>
<br>

A **Alpha** nasceu pra programar em português, sem acento fora de aspas e com sintaxe curta (`*campo`, `@botão`, `&mensagem`). Um tradutor em **Python** converte o `.alf` em HTML + JS prontos pra abrir no navegador.

</details>

<details>
<summary><b>🪪 Páginas de bio com links</b></summary>
<br>

O **biohtml** é uma bio com links acessíveis, feita em HTML puro e programada por mim. Dá pra personalizar uma pra qualquer pessoa.

</details>

<details>
<summary><b>🗂️ GitHub como backend</b></summary>
<br>

No **joaoricardo**, qualquer arquivo é servido por URL direta e fica guardado num repositório público; a Vercel só roda o código do site. Sites inteiros (HTML + CSS + JS) funcionam com a estrutura de pastas preservada, cada arquivo com o `Content-Type` certo. O que não dá: `.php` e outras linguagens de servidor não executam, aparecem como texto.

</details>

<details>
<summary><b>🪟 Interfaces "liquid glass"</b></summary>
<br>

Painéis translúcidos, esferas de luz em movimento e paleta que muda conforme o conteúdo. Foi a linguagem visual do blog **névoa**, onde cada post é um `.json` lido direto do GitHub.

</details>

<details>
<summary><b>🔐 Login sem sistema de usuários</b></summary>
<br>

No blog, quem pode escrever é decidido **pelo próprio GitHub**: admin ou colaborador com permissão de escrita no repo. Zero senha própria, zero cadastro.

</details>

<details>
<summary><b>🚀 Deploy na Vercel</b></summary>
<br>

Build automático a cada push, URL pública e nenhuma infraestrutura pra manter.

</details>

<img src="assets/divider.svg" width="100%" alt=""/>

## 🧰 stack

<img src="assets/stack.svg" width="100%" alt="Tecnologias que eu uso"/>

<img src="assets/divider.svg" width="100%" alt=""/>

## 🚧 mais projetos

<table>
<tr>
<td width="50%" align="center">
<a href="https://github.com/0jrpg/biohtml"><img src="assets/card-biohtml.svg" alt="biohtml, bio com links" width="100%"/></a>
</td>
<td width="50%" align="center">
<a href="https://github.com/0jrpg/joaoricardo"><img src="assets/card-files.svg" alt="joaoricardo, site de arquivos" width="100%"/></a>
</td>
</tr>
</table>

<div align="center">
<sub>também por aqui: <a href="https://github.com/0jrpg/blog">névoa</a>, um blog liquid glass em Next.js (<a href="https://blognevoa.vercel.app">blognevoa.vercel.app</a>)</sub>
</div>

### 🔭 como o joaoricardo funciona por dentro

```mermaid
flowchart LR
    A([👤 visitante]) -->|abre uma URL| B[Next.js<br/>App Router]
    B -->|busca o arquivo| C[(📁 repositório<br/>público no GitHub)]
    C -->|devolve com o<br/>Content-Type certo| B
    B --> A
    D([💻 eu]) -->|git push| C
    B -.->|roda na| E[▲ Vercel]
```

<img src="assets/divider.svg" width="100%" alt=""/>

## 📊 números

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=0jrpg&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b1020&title_color=7dd3fc&icon_color=c4b5fd&text_color=e2e8f0" alt="Stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0jrpg&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b1020&title_color=7dd3fc&text_color=e2e8f0" alt="Linguagens"/>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/0jrpg/0jrpg/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/0jrpg/0jrpg/output/github-snake.svg"/>
  <img alt="cobrinha comendo meus commits" src="https://raw.githubusercontent.com/0jrpg/0jrpg/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

<img src="assets/footer.svg" width="100%" alt="feito com vidro, névoa e alguns posts"/>

<div align="center">

<img src="assets/header.svg" alt="0jrpg" width="100%"/>

<a href="https://github.com/0jrpg"><img src="https://img.shields.io/badge/GitHub-0jrpg-0b1020?style=for-the-badge&logo=github&logoColor=7dd3fc" alt="GitHub"/></a>
<a href="https://github.com/alphalanguage/alf"><img src="https://img.shields.io/badge/Alpha-.alf-05261c?style=for-the-badge" alt="Alpha Language"/></a>
<a href="https://educaturdi.vercel.app"><img src="https://img.shields.io/badge/EducaTurdi-online-0d2552?style=for-the-badge&logo=vercel&logoColor=fde68a" alt="EducaTurdi"/></a>
<img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
<img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>

<img src="assets/terminal.svg" alt="terminal" width="100%"/>

<img src="assets/code-rain.gif" alt="chuva de código" width="100%"/>

</div>

<img src="assets/t-destaque.svg" alt="Em destaque" width="100%"/>

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

**Como rodar:** instale a dependência uma vez (`py -m pip install requests`), abra o `tradutor.py`, informe o nome do `.alf` e depois o nome do `.html` de saída (sem a extensão). O `dicionario.md` explica cada comando.

</details>

<img src="assets/t-programo.svg" alt="Com o que eu programo" width="100%"/>

<img src="assets/tiles.svg" alt="Web apps, linguagem Alpha, dados e deploy" width="100%"/>

<br>

<table>
<tr>
<td width="46%" align="center"><img src="assets/orbit.gif" alt="Tecnologias orbitando 0jrpg" width="100%"/></td>
<td width="54%" valign="top">

**Next.js + TypeScript** é a base de quase tudo: páginas, rotas, componentes e tipos.

**Supabase + PostgreSQL** guardam os dados do EducaTurdi. Em outros projetos prefiro nem ter banco: o próprio GitHub guarda o conteúdo.

**Python** entra no tradutor da linguagem **Alpha**, que converte `.alf` em HTML + JS.

**Vercel** cuida do deploy: build a cada push, URL pública e nenhuma infraestrutura pra manter.

**Interfaces liquid glass**: painéis translúcidos, esferas de luz em movimento e paleta que muda conforme o conteúdo.

</td>
</tr>
</table>

<details>
<summary><b>🗂️ GitHub como backend</b></summary>
<br>

No **joaoricardo**, qualquer arquivo é servido por URL direta e fica guardado num repositório público; a Vercel só roda o código do site. Sites inteiros (HTML + CSS + JS) funcionam com a estrutura de pastas preservada, cada arquivo com o `Content-Type` certo. O que não dá: `.php` e outras linguagens de servidor não executam, aparecem como texto.

</details>

<details>
<summary><b>🔐 Login sem sistema de usuários</b></summary>
<br>

No blog **névoa**, quem pode escrever é decidido **pelo próprio GitHub**: admin ou colaborador com permissão de escrita no repo. Zero senha própria, zero cadastro.

</details>

<details>
<summary><b>🪪 Páginas de bio com links</b></summary>
<br>

O **biohtml** é uma bio com links acessíveis, feita em HTML e programada por mim. Dá pra fazer uma pra qualquer pessoa.

</details>

<img src="assets/t-alpha.svg" alt="Alpha em ação" width="100%"/>

<div align="center">
<img src="assets/alpha-typing.gif" alt="Escrevendo um arquivo .alf e vendo a tela gerada" width="100%"/>
</div>

<img src="assets/t-fluxo.svg" alt="Do código ao ar" width="100%"/>

<img src="assets/pipeline.svg" alt="ideia, código, git push, build, no ar" width="100%"/>

<img src="assets/t-stack.svg" alt="Minha stack" width="100%"/>

<img src="assets/stack.svg" width="100%" alt="Tecnologias que eu uso"/>

<img src="assets/t-projetos.svg" alt="Mais projetos" width="100%"/>

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

<details>
<summary><b>🔭 como o joaoricardo funciona por dentro</b></summary>
<br>

```mermaid
flowchart LR
    A([👤 visitante]) -->|abre uma URL| B[Next.js<br/>App Router]
    B -->|busca o arquivo| C[(📁 repositório<br/>público no GitHub)]
    C -->|devolve com o<br/>Content-Type certo| B
    B --> A
    D([💻 eu]) -->|git push| C
    B -.->|roda na| E[▲ Vercel]
```

</details>

<img src="assets/t-numeros.svg" alt="Números" width="100%"/>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=0jrpg&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b1020&title_color=7dd3fc&icon_color=c4b5fd&text_color=e2e8f0" alt="Stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0jrpg&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b1020&title_color=7dd3fc&text_color=e2e8f0" alt="Linguagens"/>

</div>

<img src="assets/t-contato.svg" alt="Contato" width="100%"/>

<div align="center">

<a href="https://github.com/0jrpg"><img src="assets/btn-github.svg" alt="GitHub" height="52"/></a>
<a href="https://educaturdi.vercel.app"><img src="assets/btn-educaturdi.svg" alt="EducaTurdi" height="52"/></a>
<a href="https://github.com/alphalanguage/alf"><img src="assets/btn-alpha.svg" alt="Alpha" height="52"/></a>
<a href="mailto:EducaTurdi@gmail.com"><img src="assets/btn-email.svg" alt="Contato" height="52"/></a>

</div>

<img src="assets/footer.svg" width="100%" alt="feito com vidro, névoa e alguns posts"/>

<!-- 200 OK — se você abriu o código-fonte, já temos algo em comum. -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,55:1B4D2E,100:6DB33F&text=Pedro%20Linard&fontColor=FFFFFF&fontSize=56&fontAlignY=36&desc=Back-end%20Developer%20%C2%B7%20Java%20%26%20Python&descSize=18&descAlignY=58&animation=fadeIn" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=20&duration=3000&pause=1000&color=6DB33F&center=true&vCenter=true&width=640&lines=Construindo+o+que+acontece+depois+do+clique.;APIs+REST+com+Spring+Boot+e+Django.;C%C3%B3digo+que+escala+e+outra+pessoa+entende.;Do+pacote+de+rede+at%C3%A9+o+banco+de+dados." alt="typing" />

<br/>

<a href="https://www.linkedin.com/in/pedrolinard/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:pedrolin4rd@gmail.com"><img src="https://img.shields.io/badge/Email-1F2937?style=for-the-badge&logo=gmail&logoColor=EA4335" /></a>
<a href="https://www.instagram.com/pedr.py/"><img src="https://img.shields.io/badge/@pedr.py-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
<img src="https://img.shields.io/badge/status-aberto%20a%20oportunidades-6DB33F?style=for-the-badge" />

</div>

<br/>

<table>
<tr>
<td width="58%" valign="top">

### 👨‍💻 Sobre mim

Estudante de **Análise e Desenvolvimento de Sistemas**, focado em **back-end** — a camada que ninguém vê, mas que todo mundo sente quando falha.

- 💡 Construo **APIs REST**, regras de negócio e integrações com banco de dados usando **Java (Spring Boot)** e **Python (Django)**
- 🔧 No **Spring Boot**, aprofundo **POO**, **arquitetura em camadas** e **persistência com JPA**
- 🐍 No **Django**, construo **sistemas web estruturados** e modelagem de dados
- 🌐 Base em **redes de computadores** — entendo o caminho da requisição *antes* dela chegar no meu código
- 🗣️ Inglês **B1** — documentação técnica sem dificuldade

</td>
<td width="42%" valign="top">

### `pedro.json`

```json
{
  "foco": "back-end",
  "stack": [
    "Java · Spring Boot",
    "Python · Django"
  ],
  "domino": [
    "APIs REST",
    "JPA / ORM",
    "Arquitetura em camadas"
  ],
  "diferencial": "redes",
  "status": "evoluindo"
}
```

</td>
</tr>
</table>

---

### ⚡ Como eu penso uma requisição

> Cada camada com uma única responsabilidade. Simples de ler, fácil de testar, pronto pra escalar.

```mermaid
sequenceDiagram
    autonumber
    participant C as 🌐 Cliente
    participant CT as 🎯 Controller
    participant S as ⚙️ Service
    participant R as 🗂️ Repository
    participant DB as 🐘 Banco

    C->>CT: POST /pedidos (JSON)
    CT->>CT: valida entrada
    CT->>S: DTO
    S->>S: aplica regras de negócio
    S->>R: salvar(entidade)
    R->>DB: INSERT
    DB-->>R: ok
    R-->>S: entidade persistida
    S-->>CT: resposta
    CT-->>C: 201 Created
```

---

### 🛠️ Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,python,django,postgres,mysql,git,github,idea,vscode,linux,postman&theme=dark&perline=12" />

</div>

---

### 🚀 Em evolução

<div align="center">

| Área | Status |
|:---|:---:|
| Arquitetura de Software | ![](https://img.shields.io/badge/estudando-FCA130?style=flat-square) |
| Modelagem de Banco de Dados | ![](https://img.shields.io/badge/praticando-6DB33F?style=flat-square) |
| Segurança de APIs | ![](https://img.shields.io/badge/estudando-FCA130?style=flat-square) |
| Cloud Computing | ![](https://img.shields.io/badge/pr%C3%B3ximo%20deploy-61AFFE?style=flat-square) |
| Inglês B1 → B2 | ![](https://img.shields.io/badge/em%20progresso-6DB33F?style=flat-square) |

</div>

---

### 📊 Em números

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SEU_USUARIO&show_icons=true&hide_border=true&bg_color=0D1117&title_color=6DB33F&icon_color=6DB33F&text_color=C9D1D9&rank_icon=github" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO&layout=compact&hide_border=true&bg_color=0D1117&title_color=6DB33F&text_color=C9D1D9" height="165" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SEU_USUARIO&bg_color=0D1117&color=C9D1D9&line=6DB33F&point=FFFFFF&area=true&area_color=6DB33F&hide_border=true" width="100%" />

</div>

---

<details>
<summary><b>🔍 Easter egg — <code>GET /desistir</code></b></summary>

<br/>

```http
HTTP/1.1 404 Not Found

{ "erro": "Recurso não encontrado neste servidor.", "sugestao": "GET /evoluir" }
```

</details>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:6DB33F,45:1B4D2E,100:0D1117" width="100%" />

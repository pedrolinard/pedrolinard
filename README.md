<!--
  200 OK — você abriu o código-fonte do README.
  Curiosidade de quem lê o código por trás da tela. Gostei de você.
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=6DB33F&center=true&vCenter=true&width=720&lines=%3E+GET+%2Fpedro-linard+HTTP%2F1.1;%3E+200+OK;%3E+Content-Type%3A+application%2Fbackend-developer;%3E+o+que+acontece+depois+do+clique+%C3%A9+comigo." alt="GET /pedro-linard" />

### `Pedro Linard API` · `v1.0.0`

**Back-end Developer em formação** · Análise e Desenvolvimento de Sistemas

`Java` · `Spring Boot` · `Python` · `Django` · `REST` · `Redes`

</div>

> [!NOTE]
> **Este perfil é uma API.** Em vez de te contar quem eu sou, deixo você *consultar*.
> Escolha um endpoint abaixo — todas as respostas são reais.

---

### `$ curl -X GET https://api.pedrolinard.dev/v1/pedro`

```http
HTTP/1.1 200 OK
Content-Type: application/json
Accept-Language: pt-BR, en;q=0.6
X-Status: em-evolucao-constante
```

```json
{
  "nome": "Pedro Linard",
  "formacao": "Análise e Desenvolvimento de Sistemas",
  "foco": "Desenvolvimento back-end",
  "missao": "Construir soluções escaláveis, organizadas e alinhadas às boas práticas de engenharia de software",
  "stack": {
    "java":   ["Spring Boot", "JPA", "POO", "Arquitetura em camadas"],
    "python": ["Django", "Modelagem de dados", "Sistemas web estruturados"]
  },
  "experiencia": ["APIs REST", "Regras de negócio", "Integração com banco de dados", "Git"],
  "diferencial": "Redes de computadores — entendo o caminho que a requisição faz antes de chegar no meu código",
  "idiomas": { "portugues": "nativo", "ingles": "B1 — leio documentação técnica sem dificuldade" },
  "disponivel_para": ["estágio", "projetos", "colaborações"]
}
```

---

### 📑 `Endpoints disponíveis`

| Método | Endpoint | Descrição |
|:---:|:---|:---|
| ![GET](https://img.shields.io/badge/GET-61AFFE?style=flat-square) | [`/sobre`](#-get-sobre) | Quem eu sou e como penso software |
| ![GET](https://img.shields.io/badge/GET-61AFFE?style=flat-square) | [`/arquitetura`](#-get-arquitetura) | Como eu estruturo uma aplicação |
| ![GET](https://img.shields.io/badge/GET-61AFFE?style=flat-square) | [`/rede`](#-get-rede) | O que acontece antes do back-end |
| ![GET](https://img.shields.io/badge/GET-61AFFE?style=flat-square) | [`/stack`](#-get-stack) | Tecnologias e ferramentas |
| ![PUT](https://img.shields.io/badge/PUT-FCA130?style=flat-square) | [`/roadmap`](#-put-roadmap) | O que estou atualizando em mim |
| ![POST](https://img.shields.io/badge/POST-49CC90?style=flat-square) | [`/contato`](#-post-contato) | Fale comigo |

---

### 🔵 `GET /sobre`

Estudante de **Análise e Desenvolvimento de Sistemas** com foco em **back-end** — a parte do software que ninguém vê, mas que todo mundo sente quando falha.

- 💡 Desenvolvo projetos acadêmicos e pessoais com **Java (Spring Boot)** e **Python (Django)**, construindo **APIs REST**, implementando regras de negócio e integrando com banco de dados.
- 🔧 Com **Spring Boot**, aprofundo **POO**, **arquitetura em camadas** e **persistência com JPA**.
- 🐍 Com **Django**, construo **sistemas web estruturados**, modelo dados e implemento funcionalidades de back-end.
- 🌐 Tenho base em **redes de computadores**, o que muda a forma como enxergo comunicação entre sistemas e aplicações distribuídas.

```diff
- Código que só funciona.
+ Código que funciona, escala e outra pessoa consegue manter.
```

---

### 🔵 `GET /arquitetura`

> Como uma requisição atravessa uma aplicação que eu construo — cada camada com **uma** responsabilidade.

```mermaid
flowchart LR
    C(["🌐 Cliente"]) -->|HTTP / JSON| CT["🎯 Controller<br/><sub>recebe e valida</sub>"]
    CT --> S["⚙️ Service<br/><sub>regras de negócio</sub>"]
    S --> R["🗂️ Repository<br/><sub>JPA · Django ORM</sub>"]
    R --> DB[("🐘 Banco de Dados")]
    DB -.->|dados| R -.-> S -.->|DTO| CT -.->|200 OK| C

    style C  fill:#0D1117,stroke:#61AFFE,color:#61AFFE
    style CT fill:#0D1117,stroke:#6DB33F,color:#C9D1D9
    style S  fill:#6DB33F,stroke:#6DB33F,color:#0D1117
    style R  fill:#0D1117,stroke:#6DB33F,color:#C9D1D9
    style DB fill:#0D1117,stroke:#FCA130,color:#FCA130
```

---

### 🔵 `GET /rede`

> A maioria dos devs começa a pensar quando a requisição chega no controller. Eu começo antes.

```bash
$ traceroute pedro-linard
 1  estudante-ads          0.1 ms   # fundamentos, lógica, POO
 2  redes-de-computadores  1.2 ms   # TCP/IP, DNS, HTTP — como os sistemas conversam
 3  apis-rest              3.4 ms   # Spring Boot · Django
 4  banco-de-dados         5.1 ms   # modelagem, JPA, ORM
 5  arquitetura            * * *    # em rota...
 6  engenheiro-back-end    * * *    # destino final 🎯
```

---

### 🔵 `GET /stack`

<div align="center">

[![Minhas tecnologias](https://skillicons.dev/icons?i=java,spring,python,django,git,idea,vscode&theme=dark)](https://skillicons.dev)

</div>

---

### 🟠 `PUT /roadmap`

> Status `102 Processing` — atualizações em andamento.

```
arquitetura de software   [████████░░░░░░░░░░░░]  em estudo
modelagem de banco        [██████████░░░░░░░░░░]  em prática
segurança de APIs         [██████░░░░░░░░░░░░░░]  em estudo
cloud computing           [████░░░░░░░░░░░░░░░░]  próximo deploy
inglês B1 → B2            [██████████░░░░░░░░░░]  em progresso
```

<details>
<summary><b>⚠️ <code>404 — clique para ver o que não foi encontrado</code></b></summary>

<br/>

```http
HTTP/1.1 404 Not Found

{
  "erro": "Recurso 'desistir' não encontrado neste servidor.",
  "sugestao": "Tente GET /evoluir"
}
```

</details>

---

### 🟢 `POST /contato`

```bash
curl -X POST https://api.pedrolinard.dev/v1/contato \
  -H "Content-Type: application/json" \
  -d '{ "assunto": "vamos construir algo juntos?" }'
```

| Canal | Endpoint |
|:---|:---|
| 💼 LinkedIn | [linkedin.com/in/pedrolinard](https://www.linkedin.com/in/pedrolinard/) |
| 📧 Email | [pedrolin4rd@gmail.com](mailto:pedrolin4rd@gmail.com) |
| 📸 Instagram | [@pedr.py](https://www.instagram.com/pedr.py/) |

<div align="center">

<br/>

```http
HTTP/1.1 201 Created
Location: /conexoes/voce
```

<sub>⚙️ Servidor no ar · tempo de resposta: rápido · uptime: aprendendo todos os dias</sub>

</div>

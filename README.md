<div align="center">

<img src="assets/ayitistats-banner-data.png" alt="AYITISTATS" width="100%" />

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&duration=2500&pause=800&color=39FF14&background=0D111700&center=true&vCenter=true&multiline=true&repeat=true&width=780&height=100&lines=%24+ssh+geovany.laguerre%40ayitistats.org;Geovany+Batista+Polo+LAGUERRE;Data+Engineer+%40+AYITISTATS+%7C+Open+Haitian+Data" alt="Typing SVG" />

</div>

```console
geovany.laguerre@ayitistats:~$ whoami
geovany_batista_polo_laguerre

geovany.laguerre@ayitistats:~$ cat profile.yml
role:        Data Engineer · DevOps
org:         AYITISTATS (Data team, Dev Team)
mission:     open access to Haitian public data
philosophy:  scattered public data -> one open, queryable commons
now:         documenting & deploying a custom Data Commons instance
web:         geovanylaguerre.net
```

## `pipeline.md`

```console
geovany.laguerre@ayitistats:~$ tree pipeline/
```

```text
 SOURCES                 MODEL                  SERVE               ASK
┌────────────┐      ┌───────────────┐     ┌───────────────┐   ┌────────────┐
│ IHSI       │      │ StatVars      │     │ Custom        │   │ MCP server │
│ World Bank │ ───> │ MCF           │ ──> │ Data Commons  │──>│ NLP queries│
│ WHO·UNESCO │      │ DCIDs         │     │ (Google Cloud)│   │ (Python)   │
│ MSPP·BRH·MEF│     └───────────────┘     └───────────────┘   └────────────┘
└────────────┘
```

## `ls projects/`

| Project | What it does | Stack |
|---|---|---|
| **custom-data-commons** | Unifies AYITISTATS sources (IHSI, World Bank, WHO, UNESCO, MSPP, BRH, MEF…) into a single Data Commons instance for Haiti | Data Commons · Google Cloud · Python |
| **data-modeling** | Turns Haitian statistical datasets into the Data Commons format | StatVars · MCF · DCIDs |
| **ai-layer** | MCP server on top of the instance + NLP to query the data in natural language | MCP · NLP · Python |
| **devops-envs** | Team Jira environments, Google Cloud / Data Commons environment setup | Jira · Google Cloud · Docker |
| **docs-pm** | Project documentation and Jira space administration for the Data team | Confluence · Jira |

## `cat stack.yml`

```yaml
languages: [Python, SQL, TypeScript]
data:      [Data Commons, BigQuery]
infra:     [Google Cloud, Docker, Linux, Git]
tooling:   [MCP, NLP, Jira, Confluence]
```

<div align="center">

<img src="https://skillicons.dev/icons?i=python,docker,git,linux,gcp,ts,jira,confluence&theme=dark" alt="Stack icons" />

</div>

## `contact --all`

<div align="center">

[![AYITISTATS](https://img.shields.io/badge/AYITISTATS.ORG-0D1117?style=for-the-badge&logo=googlechrome&logoColor=39FF14)](https://ayitistats.org)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-0D1117?style=for-the-badge&logo=googlechrome&logoColor=39FF14)](https://geovanylaguerre.net)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0D1117?style=for-the-badge&logo=linkedin&logoColor=39FF14)](https://linkedin.com/in/geobatpo07)
[![GitHub](https://img.shields.io/badge/PERSONAL_GITHUB-0D1117?style=for-the-badge&logo=github&logoColor=39FF14)](https://github.com/Geobatpo07)

```console
geovany.laguerre@ayitistats:~$ echo $?
0
```

</div>

<div align="center">

<img src="assets/ayitistats-banner-find-your-data.png" alt="Find your data with AYITISTATS" width="100%" />

</div>

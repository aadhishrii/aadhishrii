<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Aadhishrii+Patiil;AI+%26+Data+Software+Engineer;Building+Agentic+Systems;Databricks+%7C+RAG+%7C+LangGraph)](https://git.io/typing-svg)

![Status](https://img.shields.io/badge/status-open_to_work-brightgreen?style=flat-square)
![Role](https://img.shields.io/badge/role-AI%20%26%20Data%20Engineer-blue?style=flat-square)
![Relocate](https://img.shields.io/badge/open_to_relocate-Yes-9146FF?style=flat-square)

</div>

<br>

```bash
aadhi@dev:~$ whoami
```
```
Aadhishrii Patiil
AI & Data Software Engineer · Agentic Systems · Databricks
Currently building agents that know when NOT to trust themselves
```

```bash
aadhi@dev:~$ cat philosophy.md
```
```
> I build for real users in high-stakes environments.
> Before I write code: why does this exist, who does it serve,
  how will I know if it worked.
```

```bash
aadhi@dev:~$ ls experience/
```
```
systems-plus-technologies/   data-eng-intern     Jun 2026 – Present
usc/                         research-associate  Feb 2025 – Feb 2026
trini-ai/                    swe-intern          Jun 2024 – Sep 2024
royal-hospital-for-women/    swe-thesis          Sep 2021 – Aug 2022
```

```bash
aadhi@dev:~$ cd projects/ridestream && cat README.md
```
```
RideStream — a query layer for people who don't know the schema

the problem:
  a STAR schema is efficient to query and useless to someone
  who doesn't know it exists.

what I built:
  Event Hub -> ADF -> Databricks medallion pipeline, modeled into
  a STAR schema (SCD Type 1 + Type 2), with a Claude-backed
  NL-to-SQL layer on top — validated and logged, not "trust the LLM
  and hope."

how I actually tested it:
  20 questions across joins, aggregations, and deliberately
  out-of-scope requests. 100% success on answerable ones, 100%
  correct rejection on the rest — including a DELETE it should
  never have generated in the first place.

stack: Azure Event Hub · Data Factory · Databricks · PySpark · Delta Lake · Claude API
```

```bash
aadhi@dev:~/projects/ridestream$ cd ../studyos && cat README.md
```
```
StudyOS — a study assistant that actually knows my notes

why:
  generic chatbots don't know what I've already learned.
  I wanted answers grounded in MY Notion knowledge base,
  not plausible-sounding fiction.

the hard part wasn't the chat UI:
  it was retrieval — chunking, embeddings, and grounding
  evals that catch the assistant when it starts making
  things up.

stack: LangChain · LangGraph · Claude API · ChromaDB
```

```bash
aadhi@dev:~/projects/studyos$ cd ../buena && cat README.md
```
```
Buena — property PDFs that stop needing a human typist

before:
  one property document = 14 rows of manual data entry.

after:
  AI reads the PDF once, extracts structured records,
  human reviews ONE submission instead of retyping 14.

honest note:
  AI extraction on messy real docs fails in weird ways —
  I spent as much time on the 87-test safety net as I did
  on the extraction pipeline itself.

stack: Next.js · NestJS · PostgreSQL · Prisma · Claude API
```

```bash
aadhi@dev:~$ cat stack.json
```
```json
{
  "agentic_ai":  ["LangChain", "LangGraph", "RAG", "Tool Calling", "Prompt Engineering"],
  "languages":   ["Python", "SQL", "TypeScript", "JavaScript"],
  "frontend":    ["React", "Next.js"],
  "backend":     ["Node.js", "NestJS", "FastAPI", "Flask", "GraphQL"],
  "data_cloud":  ["PostgreSQL", "PySpark", "Azure Databricks", "Azure Event Hub", "Azure Data Factory", "Delta Lake", "Jinja", "Docker"],
  "ai_tools":    ["Claude API", "OpenAI API", "ChromaDB", "SentenceTransformers"]
}
```

<div align="center">
<img src="https://skillicons.dev/icons?i=python,typescript,react,nodejs,fastapi,graphql,postgres,docker,azure,git" />
</div>

```bash
aadhi@dev:~$ cat education.log
```
```
[2023-01 -> 2025-01]  University of Southern California
                      M.S. Computer Science

[2018-08 -> 2022-12]  University of New South Wales
                      B.E. Software Engineering
```

```bash
aadhi@dev:~$ cat writing/index.md
```
```
- "Bad Data Used to Fail Loudly. Now It Just Lies to You"
  -> why RAG failures hide instead of crash, and what data
     engineering discipline still protects against
  -> https://aadhishrii.hashnode.dev/bad-data-used-to-fail-loudly-now-it-just-lies-to-you

- "Designing for NICU Systems"
  -> the gap between technically correct and actually usable
  -> https://aadhishrii.hashnode.dev/what-building-a-nicu-app-taught-me-about-designing-for-real-users
```

```bash
aadhi@dev:~$ ./status --check
```
```
[ok]  open to: AI Builder / Applied AI / Forward Deployed Engineer roles
[ok]  reachable: aadhipatiil@gmail.com
[ok]  open to relocation: yes
[..]  currently: Databricks Certified Data Engineer Associate (in progress)
```

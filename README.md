# Portfólio GRC — Plural Consulting

Repositório de documentação de Segurança da Informação desenvolvido sobre a empresa fictícia **Plural Consulting**, construído a partir de um cenário realista baseado em problemas comuns enfrentados por pequenas e médias empresas brasileiras.

---

## O Cenário

A Plural Consulting é uma consultoria empresarial com foco no setor agro, com cerca de 50 colaboradores, operação predominantemente remota e uso de dispositivos pessoais (BYOD). Como muitas empresas do seu porte, ela cresceu sem estrutura formal de segurança da informação — a proteção dos dados dependia do bom senso de cada pessoa e de controles pontuais mantidos por um único profissional de TI.

Ao longo dos anos, a empresa acumulou riscos silenciosos: golpes de boleto recorrentes, acessos sem controle formal, dados pessoais de clientes e alunos trafegando por WhatsApp, terceiros sem contrato operando com acesso amplo a sistemas sensíveis. O ponto de ruptura veio quando um ataque de ransomware resultou na perda de um mês inteiro de dados — sem backup recente disponível para recuperação.

Foi a partir desse contexto que a Plural decidiu implementar um programa formal de Segurança da Informação. Este repositório documenta esse programa do início ao fim.

---

## Como Foi Construído

O programa foi estruturado seguindo a hierarquia documental da **ISO/IEC 27001:2022**, com três níveis:

- **Nível 1 — Política:** define os princípios e diretrizes estratégicas aprovadas pela alta direção
- **Nível 2 — Normas:** detalham as regras por tema, derivadas da política
- **Nível 3 — Procedimentos:** descrevem o passo a passo operacional para execução de cada controle

Cada documento foi construído a partir do contexto real da Plural — os gaps identificados, os incidentes sofridos e as características específicas da operação (BYOD, terceiros sem contrato, ausência de classificação de dados) foram o ponto de partida para cada norma e procedimento. Nada foi criado de forma genérica.

Os frameworks de referência utilizados foram:

- **ISO/IEC 27001:2022** — estrutura do SGSI e controles do Anexo A
- **ISO 31000:2018** — gestão de riscos
- **LGPD (Lei 13.709/2018)** — conformidade no tratamento de dados pessoais

---

## Estrutura do Repositório

```
grc-portfolio-plural-consulting/
├── politicas/          # Nível 1 — Documentos estratégicos
├── normas/             # Nível 2 — Documentos normativos por tema
├── procedimentos/      # Nível 3 — Procedimentos operacionais
└── risk-assessment/    # Gestão de riscos — inventário, matriz e plano de tratamento
```

---

## Documentos Disponíveis

### Políticas

| Código | Documento |
|--------|-----------|
| PSI-001 | [Política de Segurança da Informação](politicas/PSI-001-Plural-Consulting.pdf) |

### Normas

| Código | Documento |
|--------|-----------|
| NCA-001 | [Norma de Controle de Acesso](normas/NCA-001-Plural-Consulting.pdf) |
| NUAD-001 | [Norma de Uso Aceitável de Dispositivos (BYOD)](normas/NUAD-001-Plural-Consulting.pdf) |
| NCI-001 | [Norma de Classificação da Informação](normas/NCI-001-Plural-Consulting.pdf) |
| NGI-001 | [Norma de Gestão de Incidentes de Segurança](normas/NGI-001-Plural-Consulting.pdf) |
| NTF-001 | [Norma de Gestão de Terceiros e Fornecedores](normas/NTF-001-Plural-Consulting.pdf) |

### Procedimentos

| Código | Documento |
|--------|-----------|
| PCA-001 | [Procedimento de Concessão de Acesso](procedimentos/PCA-001-Plural-Consulting.pdf) |
| PRA-001 | [Procedimento de Revogação de Acesso](procedimentos/PRA-001-Plural-Consulting.pdf) |
| PPFD-001 | [Procedimento de Resposta a Perda ou Furto de Dispositivo](procedimentos/PPFD-001-Plural-Consulting.pdf) |
| PRIS-001 | [Procedimento de Resposta a Incidentes de Segurança](procedimentos/PRIS-001-Plural-Consulting.pdf) |
| PBVI-001 | [Procedimento de Backup e Verificação de Integridade](procedimentos/PBVI-001-Plural-Consulting.pdf) |
| POT-001 | [Procedimento de Onboarding de Terceiros](procedimentos/POT-001-Plural-Consulting.pdf) |
| PFTT-001 | [Procedimento de Offboarding de Terceiros](procedimentos/PFTT-001-Plural-Consulting.pdf) |
| PDSI-001 | [Procedimento de Descarte Seguro de Informações](procedimentos/PDSI-001-Plural-Consulting.pdf) |

### Risk Assessment

| Documento | Descrição |
|-----------|-----------|
| [RiskAssessment-Plural-Consulting.xlsx](risk-assessment/RiskAssessment-Plural-Consulting.xlsx) | Inventário de 15 ativos, matriz de 24 riscos (Probabilidade × Impacto) e plano de tratamento com controles ISO 27001 referenciados |

---

## Sobre o Autor

Profissional de GRC com background em comunicação corporativa e operações, com foco em governança, gestão de riscos e conformidade aplicados ao contexto brasileiro.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/erick-alves-sec/)

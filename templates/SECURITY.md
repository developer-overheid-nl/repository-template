# Securitybeleid

## Ondersteunde versies
In deze tabel staat beschreven welke versies van onze codebase worden ge-update door middel van securitypatches.

| Versie  | Ondersteund       |
| ------- | ------------------|
| 1.x.x   | ✅                |
| < 1.0   | ❌                |

## Een kwetsbaarheid melden

We nemen de beveiliging van onze software serieus. Als je denkt dat je een beveiligingskwetsbaarheid hebt gevonden, meld deze dan zoals hieronder beschreven.

> **Meld beveiligingskwetsbaarheden nooit via openbare GitHub issues.**

### Hoe te melden

Stuur een e-mail naar: [{{ securityEmail }}](mailto:{{ securityEmail }})

Vermeld indien mogelijk de volgende informatie:
- Type kwetsbaarheid (bijv. buffer overflow, SQL injection, cross-site scripting, etc.)
- Volledige paden van bronbestanden die verband houden met de kwetsbaarheid.
- De locatie van de getroffen broncode (tag/branch/commit of directe URL).
- Speciale configuratie die nodig is om de kwetsbaarheid te reproduceren.
- Stap-voor-stap instructies om de kwetsbaarheid te reproduceren.
- Proof-of-concept of exploit code (indien mogelijk).
- Impact van de kwetsbaarheid, inclusief hoe een aanvaller deze zou kunnen misbruiken.

### Wat kun je verwachten

- Je ontvangt binnen 3 werkdagen een bevestiging van je melding.
- We houden je op de hoogte van de voortgang van de oplossing.
- We streven ernaar kritieke kwetsbaarheden binnen 90 dagen op te lossen.
- We vermelden je in onze release notes (tenzij je liever anoniem blijft).

### Responsible Disclosure

Dit project volgt de [Responsible Disclosure richtlijnen](https://www.ncsc.nl/documenten/publicaties/2019/mei/01/cvd-leidraad) van het NCSC (Nationaal Cyber Security Centrum).

- We verzoeken je de kwetsbaarheid niet openbaar te maken totdat we deze hebben verholpen.
- We stemmen het tijdschema voor openbaarmaking met je af.
- Voor coördinatie van kwetsbaarheden werken we samen met het NCSC en volgen we het [Coordinated Vulnerability Disclosure (CVD)](https://www.ncsc.nl/onderwerpen/coordinated-vulnerability-disclosure) proces.

## Beveiligingsupdates

Beveiligingsupdates worden uitgebracht als patch-versies en gedocumenteerd in onze [CHANGELOG.md](CHANGELOG.md).

## Contact

Voor vragen over dit beleid, neem contact op via: [{{ securityEmail }}](mailto:{{ securityEmail }}).
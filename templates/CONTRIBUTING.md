# Bijdragen aan {{ name }}

Allereerst bedankt dat je wilt bijdragen aan dit project! Zonder jouw input
wordt dit nooit een beter open source project.

## Code of Conduct

Dit project hanteert een [Code of Conduct](CODE_OF_CONDUCT.md). Door bij te
dragen aan dit project ga je akkoord met de voorwaarden hiervan.

## Hoe kan je bijdragen?

Er zijn verschillende manieren om bij te dragen aan dit project:

### Meld een bug

Heb je een bug gevonden? Maak dan een [issue]({{ issueLink }}) aan met:

- Een duidelijke en beschrijvende titel
- Stappen om de bug te reproduceren
- Verwacht gedrag vs. daadwerkelijk gedrag
- Screenshots of foutmeldingen (indien van toepassing)
- Je omgeving (OS, browserversie, etc.)

### Features voorstellen

Heb je een idee voor een nieuwe feature? Open een issue met:

- Een duidelijke beschrijving van de feature
- Waarom deze feature waardevol zou zijn
- Eventuele voorbeelden of mockups

### Documentatie verbeteren

Documentatie kan altijd beter! Pull requests voor verbeteringen aan de
documentatie zijn zeer welkom.

### Code bijdragen

Wil je code bijdragen? Volg dan onderstaand proces.

## Ontwikkelproces

### 1. Fork en clone de repository

```bash
git clone {{ url }}
cd directory-name
```

### 2. Maak een nieuwe branch

```bash
git checkout -b feature/mijn-nieuwe-feature
```

Of voor bugfixes:

```bash
git checkout -b fix/issue-nummer-korte-beschrijving
```

### 3. Installeer dependencies

```bash
# PROJECTSPECIFIEK: pas dit aan voor jouw project
npm install
# of
pip install -r requirements.txt
# of
composer install
```

### 4. Maak je wijzigingen

- Schrijf duidelijke, leesbare code
- Voeg tests toe voor nieuwe functionaliteit
- Update documentatie waar nodig

### 5. Test je wijzigingen

```bash
# PROJECTSPECIFIEK: pas dit aan voor jouw project
npm test
# of
pytest
# of
./vendor/bin/phpunit
```

### 6. Commit je wijzigingen

We gebruiken [Conventional Commits](https://www.conventionalcommits.org/) voor
onze commit messages:

```
<type>(<scope>): <beschrijving>

[optionele body]

[optionele footer]
```

Types:

- `feat`: Een nieuwe feature
- `fix`: Een bug fix
- `docs`: Documentatie wijzigingen
- `style`: Code style wijzigingen (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Toevoegen of wijzigen van tests
- `chore`: Onderhoud (dependencies, etc.)

Voorbeeld:

```
feat(auth): voeg two-factor authenticatie toe

Implementeert TOTP-based 2FA voor gebruikers.

Closes #123
```

### 7. Push naar je fork

```bash
git push origin feature/mijn-nieuwe-feature
```

### 8. Open een Pull Request

- Geef je PR een duidelijke titel en beschrijving
- Link gerelateerde issues
- Zorg dat alle tests slagen
- Wacht op review van een maintainer

## Ontwikkelomgeving

**PROJECTSPECIFIEK**: Voeg specifieke setup instructies toe voor jouw project

### Vereisten

- Node.js >= 18.x / Python >= 3.9 / PHP >= 8.1
- Git >= 2.30
- [Andere specifieke dependencies]

### Lokaal draaien

```bash
# Development server starten
npm run dev
# of
python manage.py runserver
# of
php artisan serve

# Build maken
npm run build
```

### Development tools

- [Link naar lokale development documentatie]
- [Link naar database setup instructies]
- [Link naar API documentatie]

## Testing

**PROJECTSPECIFIEK**: Voeg test-instructies toe

```bash
# Alle tests draaien
npm test

# Met coverage
npm run test:coverage

# Specifieke test
npm test -- auth.test.js

# Linting
npm run lint

# Formatting
npm run format
```

### Test requirements

- Nieuwe features moeten minimaal 80% code coverage hebben
- Alle tests moeten slagen voordat een PR gemerged wordt
- Voeg zowel unit als integration tests toe waar relevant

## Toegankelijkheid (Accessibility)

Voor Nederlandse overheidsprojecten is toegankelijkheid wettelijk verplicht:

- Volg [WCAG 2.1](https://www.w3.org/WAI/WCAG21/quickref/) niveau AA
- Test met screenreaders (NVDA/JAWS)
- Zorg voor keyboard navigatie
- Gebruik semantische HTML
- Test kleurcontrast (minimaal 4.5:1)

## Beveiliging (Security)

- Meld beveiligingsproblemen **NIET** via publieke issues
- Gebruik het proces beschreven in [SECURITY.md](SECURITY.md)
- Volg [OWASP Top 10](https://owasp.org/www-project-top-ten/) best practices
- Voor overheidsprojecten: houd rekening met
  [BIO](https://www.digitaleoverheid.nl/overzicht-van-alle-onderwerpen/cybersecurity/kaders-voor-cybersecurity/baseline-informatiebeveiliging-overheid/)
  normen

## Community

**PROJECTSPECIFIEK**: Voeg relevante community informatie toe

- Community calls: zijn er vaste community calls?
- Chat: link naar bijvoorbeeld het Slack-kanaal.
- Mailinglist: link naar de nieuwsbrief.
- Roadmap: link naar de roadmap.

## Licentie

Door bij te dragen aan dit project ga je ermee akkoord dat je bijdragen worden
gelicenseerd onder de [EUPL-1.2](LICENCE.md) licentie. Dit betekent dat:

- Je het auteursrecht behoudt op je bijdragen
- Je bijdragen beschikbaar komen onder dezelfde open source licentie
- De code gebruikt mag worden door andere overheidsorganisaties

## Erkenning

Bijdragers worden vermeld in:

- [CHANGELOG.md](CHANGELOG.md) bij elke release
- De [AUTHORS](AUTHORS.md) file (optioneel)

---

Bedankt voor je bijdrage!

_Dit project wordt onderhouden door {{ mainCopyrightOwner }} en de open source
community._

# {{ name }}

{{ longDescription }}

Ga naar [{{ landingURL }}]({{ landingURL }}) voor meer informatie.

## Features
Deze codebase bestaat uit de volgende features:

{{#features}}
- {{.}}
{{/features}}

## Aan de slag

### Vereisten

**PROJECTSPECIFIEK**: Voeg de vereisten voor jouw project toe, bijvoorbeeld:

- Node.js >= 18.x / Python >= 3.9 / PHP >= 8.1
- Git >= 2.30
- [Andere specifieke dependencies]

### Installatie

```bash
# Clone de repository
git clone {{ url }}
cd project-directory

# Installeer dependencies
npm install
# of
pip install -r requirements.txt
# of
composer install
```

### Lokaal draaien

```bash
# Development server starten
npm run dev
# of
python manage.py runserver
# of
php artisan serve
```

## Ontwikkelstatus

Dit project heeft de status: **{{ developmentStatus }}**

## Bijdragen

Leuk dat je overweegt om bij te dragen in dit project. Lees onze [CONTRIBUTING.md](CONTRIBUTING.md) voor meer informatie over hoe je kunt bijdragen.

### Gedragscode

Dit project hanteert een [gedragscode](CODE_OF_CONDUCT.md). Door bij te dragen aan dit project ga je akkoord met de voorwaarden hiervan.

## Security

Heb je een potentieel securityissue gevonden? Fijn dat je de moeite hebt genomen om hier in te duiken. Hoe je op een veilige manier melding kan maken vind je in [SECURITY.md](SECURITY.md).

## Licentie

Licensed under the [EUPL-1.2](LICENCE.md)

## Contact

{{#contacts}}
Naam: {{ name }}\
{{#email}}Email: {{ email }}\{{/email}}
{{#affiliation}}Organisatie: {{ affiliation }}\{{/affiliation}}
{{#phone}}Telefoon: {{ phone }}\{{/phone}}

{{/contacts}}
## Meer informatie

- [publiccode.yml](publiccode.yml) - Metadata volgens de publiccode.yml standaard

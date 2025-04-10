# Obywatel BIELIK Docs

Repozytorium zawierające dokumentację projektu Obywatel BIELIK. Znajdują się tutaj zarówno dokumentacja techniczna, jak i materiały dla użytkowników i współtwórców projektu.

## Opis projektu

Obywatel BIELIK to aplikacja służąca do gromadzenia opisów zdjęć (anotacji) przez społeczność, w tym seniorów i lokalnych aktywistów. Aplikacja umożliwia użytkownikom opisywanie losowych zdjęć lub dodawanie własnych zdjęć wraz z opisami.

## Struktura dokumentacji

```
obywatel-bielik-docs/
├── architecture/                 # Dokumentacja architektoniczna
│   ├── diagrams/                 # Diagramy architektoniczne (C4, UML)
│   ├── system-overview.md        # Przegląd systemu
│   └── component-descriptions.md # Opisy komponentów
├── api/                          # Dokumentacja API
│   ├── openapi.yaml              # Specyfikacja OpenAPI
│   └── endpoints/                # Szczegółowe opisy endpointów
├── database/                     # Dokumentacja bazy danych
│   ├── schema.md                 # Opis schematu
│   ├── erd.png                   # Diagram ERD
│   └── migrations.md             # Zasady migracji
├── user-guides/                  # Przewodniki dla użytkowników
│   ├── getting-started.md        # Pierwsze kroki
│   ├── image-annotation.md       # Tworzenie anotacji zdjęć
│   ├── achievements.md           # System osiągnięć i gamifikacji
│   └── screenshots/              # Zrzuty ekranu aplikacji
├── dev-guides/                   # Przewodniki dla deweloperów
│   ├── setup.md                  # Konfiguracja środowiska
│   ├── coding-standards.md       # Standardy kodowania
│   ├── testing.md                # Testowanie
│   └── deployment.md             # Wdrażanie
├── design/                       # Dokumentacja projektowa
│   ├── ui-kit/                   # Elementy interfejsu
│   ├── wireframes/               # Szkice interfejsu
│   ├── mockups/                  # Makiety interfejsu
│   └── styleguide.md             # Wytyczne stylistyczne
├── legal/                        # Dokumenty prawne
│   ├── privacy-policy.md         # Polityka prywatności
│   ├── terms-of-service.md       # Warunki korzystania z usługi
│   └── license.md                # Informacje o licencji
├── meetings/                     # Notatki ze spotkań projektowych
├── assets/                       # Zasoby (logo, materiały graficzne)
└── research/                     # Badania i materiały referencyjne
```

## Dokumentacja API

Dokumentacja API jest generowana automatycznie na podstawie specyfikacji OpenAPI. Aktualna wersja jest dostępna pod adresem Dokumentacja API jest generowana automatycznie na podstawie specyfikacji OpenAPI. Aktualna wersja jest dostępna pod adresem [https://xxzu-5a3s-xcvy.f2.xano.io/api:jMvWid_x]https://xxzu-5a3s-xcvy.f2.xano.io/api:jMvWid_x)..

## Przewodniki dla użytkowników

Przewodniki dla użytkowników są dostępne w formie:
- Interaktywnych przewodników w aplikacji (onboarding)
- Dokumentów PDF do pobrania
- Stron pomocy w formatach Markdown i HTML

## Przewodniki dla deweloperów

Przewodniki dla deweloperów zawierają:
- Instrukcje konfiguracji środowiska
- Standardy kodowania
- Wytyczne dotyczące testowania
- Procedury code review i pull requestów
- Instrukcje wdrażania

## Utrzymanie dokumentacji

### Aktualizacje dokumentacji

1. Dokumentacja powinna być aktualizowana równolegle z kodem
2. Każda znacząca zmiana w API, bazie danych lub interfejsie użytkownika powinna być odzwierciedlona w dokumentacji
3. Pull requesty bez odpowiedniej aktualizacji dokumentacji nie powinny być akceptowane

### Narzędzia

- Dokumentacja jest pisana w formacie Markdown
- Diagramy są tworzone przy użyciu narzędzi PlantUML, Mermaid, draw.io
- Dokumentacja API jest generowana z kodu źródłowego przy użyciu narzędzi kompatybilnych z OpenAPI

## Jak korzystać z dokumentacji

### Użytkownicy

1. Zacznij od przewodnika `user-guides/getting-started.md`
2. Zapoznaj się z przewodnikami dotyczącymi konkretnych funkcjonalności
3. W razie problemów, sprawdź sekcję FAQ

### Deweloperzy

1. Zacznij od `dev-guides/setup.md`
2. Zapoznaj się z `architecture/system-overview.md`
3. Przed rozpoczęciem prac przeczytaj `dev-guides/coding-standards.md`

## Społeczność i wkład

Zachęcamy do współtworzenia dokumentacji:

1. Zgłaszaj problemy i sugestie poprzez system Issues
2. Proponuj zmiany poprzez Pull Requesty
3. Dołącz do dyskusji w sekcji Discussions

## Licencja

Dokumentacja projektu jest udostępniana na licencji [licencja]. Szczegółowe informacje w pliku LICENSE.

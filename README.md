# Git-verkstad – Pass 1

KodBloggen är ett enkelt webbprojekt som används under Git-verkstadens första pass.

Projektet består av en vanlig bloggsida byggd med:

- HTML
- CSS
- JavaScript

## Starta projektet

Öppna filen `index.html` i webbläsaren.

Du kan också använda tillägget Live Server i Visual Studio Code.

## Så fungerar övningarna

Varje övning ligger i en egen branch.

Byt till den branch du vill arbeta med och läs `PROBLEM.md` för att se uppgiften.

Om du fastnar finns `SOLUTION.md` med lösningen och användbara Git-kommandon.

Du byter branch med:

```bash
git switch <branch-namn>
```

## Brancher

### Case 01 – Fel fil i commit

**Branch:** `case-01-fel-fil`

Tränar på att rätta en commit där en fil av misstag har följt med.

### Case 02 – Fel innehåll i commit

**Branch:** `case-02-fel-commit`

Tränar på att göra om en commit och behålla ändringar som inte ska ingå.

### Case 03 – Ta bort från staging

**Branch:** `case-03-unstage`

Tränar på att ta bort en ändring från staging utan att ändringen försvinner.

### Case 04 – Ångra ändringar

**Branch:** `case-04-angra-andringar`

Tränar på att ångra lokala ändringar och återställa en fil.

### Case 05 – Tidigare commit

**Branch:** `case-05-tidigare-commit`

Tränar på att undersöka Git-historiken och gå tillbaka till en tidigare commit.

### Case 06 – Partial commit

**Branch:** `case-06-partial-commit`

Tränar på att välja vilka delar av en fil som ska ingå i en commit.

## Rekommenderad ordning

1. Case 01
2. Case 02
3. Case 03
4. Case 04
5. Case 05
6. Case 06

## Tips

Använd `git status` ofta för att kontrollera vad som händer i Git.

Läs `PROBLEM.md` för att förstå scenariot och uppgiften. Där finns även ett tips som hjälper dig att komma igång.

Försök lösa uppgiften själv först. Om du fastnar kan du använda `SOLUTION.md` som vägledning.

## Projektets filer

```text
git-verkstad-pass-1/
├── README.md
├── index.html
├── style.css
└── script.js
```
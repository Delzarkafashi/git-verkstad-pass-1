# Lösning

## Nyckelkommandon

```bash
git status
git add -p
git commit
git status
```

## Därför händer det

Du har gjort flera ändringar i samma fil, men alla ändringar ska inte ingå i samma commit.

Git sparar ändringarna i mindre delar, vilket gör att du kan välja exakt vilka ändringar som ska läggas i staging och ingå i nästa commit.

## Tips

- Använd `git status` för att se vilka filer som har ändrats.
- Använd `git add -p` för att välja vilka ändringar som ska läggas i staging.
- I det här caset ska du bara committa de ändringar som hör till uppgiften.
- Kontrollera med `git status` att övriga ändringar fortfarande finns kvar i arbetskatalogen.
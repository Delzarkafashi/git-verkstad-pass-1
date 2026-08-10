# Lösning

## Nyckelkommandon

```bash
git status
git restore --staged <filnamn>
git status
```

## Därför händer det

När du använder `git add` läggs filens ändringar i staging och blir redo att ingå i nästa commit.

Git sparar fortfarande ändringarna i arbetskatalogen även om filen tas bort från staging.

## Tips

- Använd `git status` för att se vilka filer som finns i staging.
- Använd `git restore --staged <filnamn>` för att ta bort filen från staging.
- Kontrollera med `git status` att filen inte längre är staged.
- Kontrollera att ändringarna fortfarande finns kvar i arbetskatalogen.
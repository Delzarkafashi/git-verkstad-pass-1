# Lösning

## Nyckelkommandon

```bash
git status
git restore <filnamn>
git status
```

## Därför händer det

Ändringarna finns bara i arbetskatalogen och har ännu inte blivit committade.

Git kan därför återställa filen till den senaste committade versionen och ta bort de lokala ändringarna.

## Tips

- Använd `git status` för att se vilka filer som har ändrats.
- Använd `git restore <filnamn>` för att ångra ändringar i en specifik fil.
- Om flera filer ska återställas kan du ange flera filnamn.
- Kontrollera med `git status` att ändringarna är borta.
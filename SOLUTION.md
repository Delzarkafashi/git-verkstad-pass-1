# Lösning

## Nyckelkommandon

```bash
git show --stat HEAD
git reset --soft HEAD~1
git restore --staged <filnamn>
git commit
git status
```

## Därför händer det

Den senaste commiten innehåller fler ändringar än den borde eftersom fel innehåll följde med när commiten skapades.

Genom att flytta tillbaka den senaste commiten kan du välja om vilka ändringar som ska ingå och sedan skapa commiten på nytt.

## Tips

- Använd `git show --stat HEAD` för att se vad den senaste commiten innehåller.
- `git reset --soft HEAD~1` tar bort den senaste commiten men behåller ändringarna.
- Använd `git restore --staged <filnamn>` för de ändringar som inte ska vara med i den nya commiten.
- Kontrollera med `git status` innan du skapar den nya commiten.
# Lösning

## Nyckelkommandon

```bash
git status
git show --stat HEAD
git rm <filnamn>
git commit --amend --no-edit
git status
```

## Därför händer det

Filen följde med när den senaste commiten skapades och blev därför en del av commiten.

Eftersom felet finns i den senaste commiten kan du ta bort filen och sedan ändra samma commit i stället för att skapa en helt ny commit.

## Tips

- Använd `git show --stat HEAD` för att kontrollera vad den senaste commiten innehåller.
- Kontrollera noggrant vilken fil som ska tas bort.
- `git commit --amend --no-edit` uppdaterar den senaste commiten utan att ändra commit-meddelandet.
- Kontrollera med `git status` när du är klar.
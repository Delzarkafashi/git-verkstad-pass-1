# Lösning

## Nyckelkommandon

```bash
git log --oneline
git reset --hard <commit-id>
git status
```

## Därför händer det

Git sparar projektets historik i commits.

Genom att välja en tidigare commit kan du återställa projektet till exakt det läge som fanns när den commiten skapades.

## Tips

- Använd `git log --oneline` för att hitta rätt commit.
- Kontrollera commit-id noggrant innan du återställer.
- `git reset --hard <commit-id>` återställer både historiken och filerna till den valda commiten.
- Kontrollera med `git status` när du är klar.
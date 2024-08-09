
# GIT

I denna lektion kommer vi gå igenom Best Practices för att använda Git. Vi kommer att gå igenom

- Vad är Git?- Besvarat i tidigare lektion
- git init - Skapa ett nytt Git-repository
- git clone - Klona ett Git-repository
- git add - Lägg till ändringar i Git (. för att lägga till alla ändringar)
- git commit -m "Meddelande" - Commita ändringar
- git push - Pusha ändringar till ett remote repository (-u origin main för att sätta default remote repository)
- git pull - Hämta ändringar från ett remote repository
- git branch - Skapa en ny branch

## Git best practices
Utse en "main" branch som är den branch som alltid ska vara deployad. Alla ändringar ska göras i en separat branch och sedan mergas in i main när de är klara. Detta för att undvika att deploya ofärdig kod.

Innan du pushar dina ändringar, se till att alltid köra `git pull` för att hämta eventuella ändringar från remote repository Samt hantera eventuella konflikter som kan uppstå.

När du skriver commit-meddelanden, se till att de är tydliga och beskrivande. Detta för att underlätta för andra utvecklare att förstå vad som har ändrats. Dela gärna upp större ändringar i mindre commits för att göra det enklare att följa historiken.
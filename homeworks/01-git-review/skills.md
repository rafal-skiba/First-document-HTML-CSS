# Zadanie 6 - Git Review

## Umiejętności programisty, które nabyłem w poprzednim tygodniu:

***
  
### *Umiejętności nabyte podczas powtórki preworka*: 
* uporządkowałem wiedzę za zakresu elementów liniowych oraz blokowych
 * uporządkowałem wiedzę za zakresu modelu pudełkowego CSS
 * zrobiłem notatki o najważniejszych selektorach używanych w CSS
 * uporządkowałem wiedzę za zakresu praktycznego używania CSS w dokumencie HTML
 * uporządkowałem wiedzę za zakresu CSS Grid oraz Flexbox
 

***
### *Nowe umiejętności nabyte podczas pierwszych zajęć kursu*: 
* struktura pracy na poszczególnych gałęziach modelu **git flow**:
    * **master** – produkcyjna wersja aplikacji (branch zgodny z produkcją),
    * **develop** - głowny branch developerski, czyli tak zwany "nieoficjalny" branch master, Z tego branch możemy tworzyć swoje gałęzie robocze i następnie mergować zmiany do branży develop,
    * **feature** – branch na którym pracuje na codzień developer,  
    * **release** – nowa wersja aplikacji przed deployem na produkcję. To właśnie wersja aplikacji   
    z tego brancha trafia na produkcję,
    * **hotfix** - Jedyna galąź bazująca na branch master, tutaj szybko naprawiamy bugi kodu produkcyjnego.
* przećwiczenie pracy na poszczególnych gałęziach modelu git flow
* wyjaśnienie pojęcia pull request 

***
Komendy, których użyłem aby wykonać commit lokalny, a następnie wysłać go do zdalengo repozytorium na GitHub.

``` 
1. git add skills.md
```
``` 
2. git commit -m "Lists skills"
```
``` 
3. git push origin master
```

---
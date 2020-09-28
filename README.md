# Cheatsheet

## Unul dintre voi, prima oara, creaza repo-ul local cu create-react-app
- `npm  init react-app nume-aplicatie`
- Teorectic create react app a creat deja un repo de git (daca nu: `git init`, `git add .`, `git commit -m 'Initial commit'`)
- Te duci pe github.com si creezi un repo
- Te intorci in folderul local si continui
- `git remote add origin <url-copiat-de-la-github>`
- `git push -u origin master`

## Colaboratorii prima data
- Se duc pe giuthub si copiaza url-ul
- `git clone <url-ul copiat> [<cale unde sa se cloneze>]`
- `npm install` / `npm i`

## Toata lumea cand incepe lucrul la o functionalitate noua
- `git switch master`
- `git pull`
- `git switch -c feature/<nume-functionalitate>`
- `git push -u feature/<nume-functionalitate>`

### Cat mai des posibil
- Lucram lucaram si iar lucram
- `git add .`
- `git commit -m "<mesaj>"`

### Cel putin odata pe zi
- `git fetch`
- `git merge origin/master`
- Testam ca codul nostru inca mai merge!!!!!!
- `git push`

## Toata lumea cand e gata functionalitate
- Intai rulam instructiunile de la sectiunea de mai sus ("Cel putin odata pe zi")
- Ne ducem pe github
- Intram la sectiunea "Pull requests"
- Selectam "New Pull Request"
- La target branch lasam "master"
- La celalalt branch selectam branch-ul nostru
- "Create pull request" si selectam la reviewers pe colegii de proiect
- Dupa ce avem aprobarea si review-ul lor ne intoarcem pe github in sectiunea Pull Requests si dam "Squash and Merge"
- Putem folosi optiunea de Delete Branch odata terminat cu succes

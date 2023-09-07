# 2-14sz
OraiMunka
1. fontos, hogy jó mappában legyünk
2. git add .
3. git commit -m "hol történt változás"
*git push local main*
4. git push origin main
*"token code"-ot kéri majd amit létre kell hozni a github oldalon*


új mappából új fájl a git repohoz való hozzáadás:
1. git init
2. git add .
3. git commit -m "index inicializálva html5"
  *git push origin main-t most nem lehet használni - meg kell mondani, hova szeretném bekötni ezt a lokális depository-t*
  *ezt meg lehet adni, ha a következő kódot hasznűljuk*
4. git remote add origin "github code részből a linket kimásoljuk"
5. git push origin master *azért nem lehet master helyett main-t használni, mert lokális depositoryban voltunk!!!*
   *ezt egybéként meg lehet nézni a "git branch" paranccsal*
   *"git branch -m main" modify-olom és master helyett mostmár main lesz, ezt újra tudjuk ellenőrizni a "get branch" paranccsal*
   *"git fetch origin master"*
   *"git merge master"*

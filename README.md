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

*-------------------------------------------------------------------------------------------------------*
*--------------------GIT COMMANDS--------------------*
*git clone https://github.com/accountname/projectname* =====> Leklónozod a depository-t abba a mappába, amelyikben éppen vagy a terminálon belül.
*git add .* =====> ???
*git init* =====> ???
*git checkout -b "name"* =====> Egy új branch ág létrehozása.
*git commit -m "something"* =====> Commenteled, hogy mit változtattál.
*git push origin main* =====> ???
*git push origin "branch name"* =====> ???
*git remote add origin "https://github.com/youraccount/projectname"* =====> ???
*git log* =====> ???
*git remote set-url origin https://username:token@github.com/username/repository.git* =====> ???
*git branch* =====> Ellenőrizni tudjuk az águnk jelenlegi jogosultságát.
*git branch -m main* =====> Modify-olod a branch ág jogosultságát és master helyett mostmár main lesz.
*git fetch origin master* =====> ???
*git merge master* =====> ???
*-------------------------------------------------------------------------------------------------------*
*--------------------TERMINAL COMMANDS--------------------*
*ls* =====> A jelenlegi könyvtárban lévő fájlok és mappákat tudjuk kilistázni vele.
*cd /folder you want to go to/* =====> Könyvtárak között tudunk vele lépkedni.
*cd..* =====> Visszalépés a jelenlegi könyvtárból a följebb lévő könyvtárba.
*mkdir "folder name"* =====> Egy új mappa létrehozása.
*rmdir "folder name"* =====> Egy bizonyos mappa törlése.
*open "File.name"* =====> Fájl megnyitása.
**
**
**

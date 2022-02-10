siehe unten für [🇩🇪 deutsche Anweisungen](#verzweigen).

# Branch Out

**Instructions**
* Create a new repository locally. 
* Add a readme file to the main branch. Add a heading to file. Make sure to add, commit your changes. 
* Create a branch named `content` and switch to the new branch.
* Add text to the readme file on the `content` branch. Don't forget to add and commit these changes.
* Go back to main and create another branch named `hotfix` from main. Note that the changes in your previous branch, `content`, are not there. 
* View all branches on terminal.

**_Note_**: Git changed the name of the default branch names from `master` to `main`. If your version of git was installed before that change, your default branch name is possibly `master` instead of `main` after initializing.

You can config the default branch name to main, if you need to:
```bash
git config --global init.defaultBranch main
```

# Verzweigen

**Anweisungen**
* Erstelle ein neu initialisiertes lokales Repository.
* Füge eine liesmich Datei zur `main` branch hinzu.
    * Füge etwas Text, wie eine Überschrift ein.
    * Stell sicher, dass die die Änderungen bekannt machst (add/staging)
    * Erzeuge einen Protokolleintrag (commit) mit einer Nachricht über die Änderung.
* Erstelle eine Branch `inhalt` und wechsle zur neuen Branch.
* Füge weiteren Text zur liesmich Datei hinzu, während du auf der `inhalt` Branch arbeitest.
    * Vergiss nicht die liesmich zu adden und committen.
* Kehre zurück auf die `main` branch und erstelle von hier aus eine weitere Branch mit Namen `korrektur`
    * Nimm zur Kenntnis, dass deine Änderungen von `inhalt` hier nicht vorhanden sind.
* Lass alle Branches auf dem Terminal ausgeben.

_Hinweis_: Git hat den Namen der Standard-Branches von `master` zu `main` entschieden. Wurde deine vresion von git vor dieser Änderung installiert, dann heißt deine Standard-Branch nach der Initialisierung möglicherweise `master` statt `main`.

Du kannst den namen der Standard-Branch einstellen, wenn es nötig ist:
```bash
git config --global init.defaultBranch main
```
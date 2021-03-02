# Arbeiten mit github.com

Vorrausetzung
Ein Account auf github.com muss angelegt sein.
Ssh muss auf den Computer laufen.

auf einer Shell folgenden Befehl ausführen:

```
ssh-keygen -b 4096
```

Diese erzeugte public key muss nach github hochgeladen werden.

```
cat ~/.ssh/id_rsa.pub
```

unter Settings - ssh-keys und gpg-keys

Danach kann mit die Repo von github.com clonen:

```
git clone git@github:<USER>/<REPO>
```

Es gibt jetzt ein gleichnamiges Verzeichnis, in das man wechselt um den Code zu ändern.

Wenn die Änderungen fertig sind, werde diese zurück nach github.com gebracht.

```
git add .

git commit -m <was wurde geändert> 

git push
```

 
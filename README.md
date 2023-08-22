# Schritt 1: Erstelle den Ordner und die README.md-Datei
mkdir git-repository_2
cd git-repository_2
echo "Hallo Welt" > README.md

# Schritt 2: Initialisiere das Git-Repository
git init

# Schritt 3: Füge Änderungen zur Staging-Area hinzu
git add .

# Schritt 4: Commite die Änderungen
git commit -m "Initialer Commit: README.md hinzugefügt"

# Schritt 6: Verbinde mit dem GitHub-Repository
git remote add origin https://github.com/dein-benutzername/second-repository.git

# Schritt 9: Lade die Änderungen auf den Remote-Branch hoch
git push -u origin master

# Schritt 10: Überprüfe den Status
git status

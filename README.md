# URL Shortener
# Was ist es?
Es ist ein URL Shortener also z.B subdomain.deinelangedomain.de/deinelangeurl2343542435325342542 zu z.B https://url.m16k.de/1


# Demo
url.m16k.de/1 sollte zu diesen Repo leiten

1. Füge zum Hinzufügen eines neuen Kurzlinks ein "Issues" hinzu, wobei der Titel der Link ist, den du kürzen möchtest (mit http(s)://) zu https://github.com/MaximilianGT500/URls/issues.
2.Du kannst nun mit der Issues-ID zugreifen mit url.m16k.de/{Issues-ID}


# Und wie kann ich es mit meine Domain benutzen?
**WARNUNG: Diese Methode zum Erstellen eines URL-Shorteners ist hackig und nicht als zuverlässig gedacht.**

1. Forke das Repo, bevor du deinen Fork klonen kannst.
2. Richte eine GitHub-Seiten für dein Geforktes Repo ein.
 2a. Klicke in dein Geforktes Repo auf die **Einstellungen** und scrollen zum Abschnitt **GitHub-Seiten**.
 2b. Wähle dann die **Main-branch** aus und klicke auf die Schaltfläche **Speichern**.
 
**How to create GitHub page**
Wenn du deine eigene Domain verwenden möchtest:
 1.[Richte deine Domain für GitHub-Seiten ein.](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain)
 2.Ändere die Domain in der **CNAME** Datei zu deiner Custom Domain
 
Wenn du die Standarddoamin der GitHub-Seite verwenden willst, Wie etwas wie: `https://<Benutzername>.github.io/<Repo-Name>/`
 1. Löschen Sie die CNAME-Datei.
 2. Ändere `**var PATH_SEGMENTS_TO_SKIP = 0;` bei 404.html zu `var PATH_SEGMENTS_TO_SKIP = 1;`.
   (Dies liegt daran, dass GitHub-Domains nach dem Hostnamen ein zusätzliches Pfadsegment (den Reponamen) haben.)

# Erstelle ein neues Repo als Datenbank. (oder du kannst dein Geforktes Repo verwenden)
 1. Ändere var GITHUB_ISSUES_LINK = "<Ihr-Github-Ausgabe-Link>"  bei 404.html entsprechend danach.
   (Format: https://api.github.com/repos/{OWNER}/{REPO}/issues/)
  
Übertrage deine Änderungen auf dein Fork-Repo, und dein kostenloser/kostengünstiger und cooler URL-Shortener ist sofort einsatzbereit!

# Lizenz
 Durch das Herunterladen stimmst du der Apache2-Lizenz zu und du darfst dieses Repository oder den Code aus diesem Repository nicht verkaufen.

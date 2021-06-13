<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="URL_Shortener_0"></a>URL Shortener</h1>
<p class="has-line-data" data-line-start="1" data-line-end="3">Was ist es?<br>
Es ist ein URL Shortener also z.B <a href="https://subdomain.deinelangedomain.de/de523465764876585868658568658658">https://subdomain.deinelangedomain.de/de523465764876585868658568658658</a> zu z.B <a href="https://url.m16k.de/1">https://maximiliangt500.github.io/URLs/1</a></p>
<h1 class="code-line" data-line-start=5 data-line-end=6 ><a id="Demo_5"></a>Demo</h1>
<p class="has-line-data" data-line-start="6" data-line-end="7"><a href="https://url.m16k.de/1">https://maximiliangt500.github.io/URLs/1</a> sollte zu diesen Repo leiten</p>
<ol>
<li class="has-line-data" data-line-start="8" data-line-end="10">Füge zum Hinzufügen eines neuen Kurzlinks ein “Issues” hinzu, wobei der Titel der Link ist, den du kürzen möchtest (mit http(s)://) zu <a href="https://github.com/MaximilianGT500/URls-db/issues">https://github.com/MaximilianGT500/URls-db/issues</a>.<br>
2.Du kannst nun mit der Issues-ID zugreifen mit <a href="http://url.m16k.de/%7BIssues-ID%7D">https://maximiliangt500.github.io/URLs/{Issues-ID}</a></li>
</ol>
<h1 class="code-line" data-line-start=12 data-line-end=13 ><a id="Und_wie_kann_ich_es_mit_meine_Domain_benutzen_12"></a>Und wie kann ich es mit meine Domain benutzen?</h1>
<p class="has-line-data" data-line-start="13" data-line-end="14"><strong>WARNUNG: Diese Methode zum Erstellen eines URL-Shorteners ist hackig und nicht als zuverlässig gedacht.</strong></p>
<ol>
<li class="has-line-data" data-line-start="15" data-line-end="16">Forke das Repo, bevor du deinen Fork klonen kannst.</li>
<li class="has-line-data" data-line-start="16" data-line-end="20">Richte eine GitHub-Seite für dein Geforktes Repo ein.<br>
2a. Klicke in dein Geforktes Repo auf die Einstellungen und scrollen zum Abschnitt GitHub-Seiten.<br>
2b. Wähle dann die Main-branch aus und klicke auf die Schaltfläche Speichern.</li>
</ol>
<h1 class="code-line" data-line-start=20 data-line-end=21 ><a id="Wie_erstellt_man_eine_Github_Seite_20"></a>Wie erstellt man eine Github Seite</h1>
<p class="has-line-data" data-line-start="21" data-line-end="22">Wenn du deine eigene Domain verwenden möchtest:</p>
<ol>
<li class="has-line-data" data-line-start="22" data-line-end="25">Richte deine Domain für GitHub-Seiten ein.<br>
2.Ändere die Domain in der CNAME Datei zu deiner Custom Domain<br>
Wenn du die Standarddoamin der GitHub-Seite verwenden willst, Wie etwas wie: <code>https://&lt;Benutzername&gt;.github.io/&lt;Repo-Name&gt;/</code></li>
<li class="has-line-data" data-line-start="25" data-line-end="26">Löschen Sie die CNAME-Datei.</li>
<li class="has-line-data" data-line-start="26" data-line-end="29">Ändere var PATH_SEGMENTS_TO_SKIP = 0; bei 404.html zu var PATH_SEGMENTS_TO_SKIP = 1;.<br>
(Dies liegt daran, dass GitHub-Domains nach dem Hostnamen ein zusätzliches Pfadsegment (den Reponamen) haben.)</li>
</ol>
<h1 class="code-line" data-line-start=29 data-line-end=30 ><a id="Erstelle_ein_neues_Repo_als_Datenbank_Freiwillig_29"></a>Erstelle ein neues Repo als Datenbank. (Freiwillig)</h1>
<ol>
<li class="has-line-data" data-line-start="30" data-line-end="33">Ändere var GITHUB_ISSUES_LINK = “&lt;Ihr-Github-Ausgabe-Link&gt;” bei 404.html entsprechend danach.<br>
(Format: <a href="https://api.github.com/repos/%7BOWNER%7D/%7BREPO%7D/issues/">https://api.github.com/repos/{OWNER}/{REPO}/issues/</a>)</li>
</ol>
<p class="has-line-data" data-line-start="33" data-line-end="34"><strong>Übertrage deine Änderungen auf dein Fork-Repo, und dein kostenloser/kostengünstiger und cooler URL-Shortener ist sofort einsatzbereit!</strong></p>
<h1 class="code-line" data-line-start=35 data-line-end=36 ><a id="Lizenz_35"></a>Lizenz</h1>
<p class="has-line-data" data-line-start="36" data-line-end="37">Durch das Herunterladen stimmst du der Apache2-Lizenz zu und du darfst dieses Repository oder den Code aus diesem Repository nicht verkaufen.</p>

---
tags:
  - help
  - issue
  - problem
  - trouble
  - missing
  - ajutor
  - problemă
---

# Centru ajutor

Ai probleme cu ceva? Suntem aici să te ajutăm! Verifică câteva soluții pentru probleme comune în bara laterală din stânga ecranului tău. Dacă problema ta nu este listată aici sau încă mai ai probleme, trimite-ne un email la [support@ppy.sh](mailto:support@ppy.sh). De asemenea, ia în considerare postarea problemei tale în [forum-ul de ajutor](https://osu.ppy.sh/community/forums/5), unde cineva va putea să te ajute.

## Secțiuni {id=sections}

Alege secțiunea care se potrivește cel mai bine cu problema ta pentru a găsi o soluție potrivită cu această problemă.

| Secțiune | Zonă de interes |
| :-- | :-- |
| [Cont](/wiki/Help_centre/Account) | suporter osu!, autentificare și accesare recuperare, modificări nume, date profil |
| [Restricții cont](/wiki/Help_centre/Account_restrictions) | Totul despre restricții, sumar, procesul de apel, motive comune și cooldown |
| [Beatmapping și Editor](/wiki/Help_centre/Beatmapping) | Păstrarea beatmap-urilor tale, proprietatea unui beatmap, sloturi beatmap |
| [Client](/wiki/Help_centre/Client) | Bug-uri și crash-uri, gameplay, conexiune, performanță |
| [Instalare și înregistrare](/wiki/Help_centre/Installation_and_registration) | Descărcarea jocului, crearea unui cont |
| [Magazin](/wiki/Help_centre/Store) | Produse, osu!go, osu!keyboard, osu!tablet |
| [Interdicții turnee](/wiki/Help_centre/Tournament_bans) | Totul despre interdicții turnee, sumar, motive comune și cooldown-uri |
| [Actualizarea la lazer](/wiki/Help_centre/Upgrading_to_lazer) | Migrarea la [următoarea versiune semnificativă](/wiki/Client/Release_stream/Lazer) osu! |
| [Site](/wiki/Help_centre/Website) | Blocharea utilizatorilor, contactare cu suportul, aparența site-ului |

## Ajută-ne să te ajutăm {id=diagnostics}

### Fișiere log {id=log-files}

**Fișierele log sunt înregistrări detaliate despre ce face client-ul jocului în orice moment dat. Le putem folosi pentru a determina cauza problemei tale.**

Aceste fișiere sunt extrem de utile și pot face trivială rezolvarea chiar și a problemelor foarte complicate.

Dacă un membru din echipa de asistență ți-a cerut aceste log-uri, uite cum poți face rost de ele:

1. Deschide osu!.
2. Apasă pe butonul de `Opțiuni` în meniul principal sau apasă `Ctrl` + `O`.
3. Scrie `release` în bara de căutare rapidă. Asta te va duce la linia actuală de release folosită de client-ul tău.
4. Asigură-te că este setată pe `Experimental`.
5. Apasă pe butonul de restart care apare în capătul ecranului dacă ai făcut vreo modificare liniei de release și aplică-le.
6. Du-te din nou în meniul de `Opțiuni` și apasă pe `Deschide folderul osu!`
7. Găsește directorul `Logs` în fereastra care se deschide.
8. Selectează fișierul de log necesar (reprezenantul de asistență îți va spune care este) și atașează-l la ticket-ul de asistență sau la postarea de pe forum.

### Vizualizator evenimente {id=event-viewer}

**Vizualizatorul de evenimente (Event Viewer) este o componentă incorporată în Windows care poate fi utilizată pentru a găsi log-urile cu crash-uri când osu! nu-ți poate oferi. Aceste log-uri cu crash-uri pot fi folosite pentru a determina ce cauzează problema ta.**

Atunci când sunt probleme cu osu! crashing, dacă osu! nu vă oferă un fișier log cu crash-ul, singurul loc unde poți găsi unul este prin vizualizatorul de evenimente.

Dacă un membru din echipa de asistență ți-a cerut să cauți un fișier log de crash în vizualizatorul de evenimente, uite cum poți face asta:

1. După ce osu! a dat crash, apasă `Win` + `R` pentru a deschide caseta de Executare.
2. În caseta de Executare scrie `eventvwr` și apasă `Enter`. Asta va deschide vizualizatorul de evenimente.
3. În vizualizatorul de evenimente, în stânga, apasă pe `Windows Logs` și apoi `Application`.
4. În dreapta, apasă pe `Filter current log`.
5. În fereastra de filtrare care s-a deschis, asigură-te că ai căsuța de `Error` bifată și apasă `OK`.
6. Apasă `Ctrl` + `F` și scrie osu! în căsuța de căutare. O să găsească primul log cu crash osu!.
7. Du-te în fila de `Details`, extinde `System` și `Event Data` prin apăsarea lor.
8. Copy the text from there and paste it into your support ticket or forum post.
8. Copiază textul de acolo și lipește-l în ticket-ul tău de asistență sau în postarea de pe forum.

### Grafic cu timpul dintre cadre {id=frame-time-graph}

**Graficul cu timpul dintre cadre este o funcție osu! care ne ajută să adunăm mai multe informați utile despre problemele de performanță pe care le-ai putea întâmpina.**

Când ne confruntăm cu probleme complicate de performanță în osu!, graficul cu timpul dintre cadre este un instrument bun pentru a ne ajuta să diagnosticăm problema și pentru a te ajuta să găsești o soluție pentru problemă.

Dacă un membru din echipa de asistență ți-a cerut să faci o filmare sau o captură de ecran cu graficul cu timpul dintre cadre, uite cum poți face asta:

1. Deschide osu!.
2. Apasă `Ctrl` + `F11` pentru a deschide graficul cu timpul dintre cadre.
3. Declanșează sau așteaptă ca problema de performanță să apară.
4. Fă o captură de ecran apăsând `Shift` + `F12`. Asta o să încarce captura de ecran pe serverele osu! și va deschide captura de ecran într-o filă de browser.
5. Copiază și lipește link-ul primit în ticket-ul tău de asistență sau pe postarea de pe forum.
6. Închide graficul cu timpul dintre cadre în același mod în care l-ai deschis, apăsând `Ctrl` + `F11`.

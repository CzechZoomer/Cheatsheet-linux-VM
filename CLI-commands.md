## Základní CLI příkazy root – správa uživatelů

| Příkaz | Popis | Syntax |
|--------|-------|--------|
| whoami | Zobrazí aktuálně přihlášeného uživatele | `whoami` |
| id | Zobrazí UID, GID a skupiny | `id [uživatel]` |
| adduser | Interaktivně přidá nového uživatele | `sudo adduser <uživatel>` |
| useradd | Přidá uživatele (méně interaktivní) | `sudo useradd -m -s /bin/bash <uživatel>` |
| passwd | Nastaví/změní heslo uživatele | `sudo passwd <uživatel>` |
| deluser | Odstraní uživatele | `sudo deluser <uživatel>` |
| userdel | Odstraní uživatele (bez složky -r pro smazání) | `sudo userdel -r <uživatel>` |
| usermod | Úprava účtu (skupiny, shell, jméno) | `sudo usermod -aG <skupina> <uživatel>` |
| chsh | Změna výchozího shellu | `sudo chsh -s /bin/bash <uživatel>` |
| groups | Zobrazí skupiny uživatele | `groups <uživatel>` |
| groupadd | Přidá novou skupinu | `sudo groupadd <skupina>` |
| groupdel | Odstraní skupinu | `sudo groupdel <skupina>` |
| gpasswd | Přidá/odebere uživatele ze skupiny | `sudo gpasswd -a <uživatel> <skupina>` |
| getent | Zobrazení záznamu uživatele | `getent passwd <uživatel>` |
| su | Přepne uživatele (nový shell) | `su - <uživatel>` |
| sudo | Spustí příkaz s právy root | `sudo <příkaz>` |
| sudo -l | Zobrazí příkazy, které uživatel může spustit přes sudo | `sudo -l` |
| last | Historie přihlášení uživatelů | `last` |
| who | Kdo je aktuálně přihlášen | `who` |
| w | Kdo je přihlášen a co dělá | `w` |

---

 - Sincronizza ed aggiorna tutti i pacchetti:
    sudo pacman -Syu

  - Installa un nuovo pacchetto:
    sudo pacman -S package_name

  - Rimuovi il pacchetto e le sue dipendenze:
    sudo pacman -Rs package_name

  - Cerca il pacchetto nel database con l'esatta espressione o parola chiave:
    pacman -Ss "search_pattern"

  - Lista dei pacchetti installati e versioni:
    pacman -Q

  - Elenca solo i pacchetti e le versioni installati in modo esplicito:
    pacman -Qe

  - Elenca i pacchetti orfani (installati come dipendenze ma non effettivamente richiesti da nessun pacchetto):
    pacman -Qtdq

  - Svuota l'intera cache di pacman:
    sudo pacman -Scc

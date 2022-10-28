- Sincronizza e aggiorna tutti i pacchetti:
    sudo pacman -Syu

  - Installa un nuovo pacchetto:
    sudo pacman -S nome_pacchetto

  - Rimuovere un pacchetto e le sue dipendenze:
    sudo pacman -Rs nome_pacchetto

  - Cerca nel database del pacchetto un'espressione regolare o una parola chiave:
    pacman -Ss "modello_ricerca"

  - Elenca i pacchetti e le versioni installati:
    pacman -Q

  - Elenca solo i pacchetti e le versioni installati in modo esplicito:
    pacman -Qe

  - Elenca i pacchetti orfani (installati come dipendenze ma non effettivamente richiesti da nessun pacchetto):
    pacman -Qtdq

  - Svuota l'intera cache di pacman:
    sudo pacman -Scc

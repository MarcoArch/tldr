dnf

  Utilità di gestione dei pacchetti per RHEL, Fedora e CentOS (sostituisce yum).
  Maggiori informazioni: https://dnf.readthedocs.io.

  - Aggiorna i pacchetti installati alle versioni più recenti disponibili:
    sudo dnf upgrade

  - Cerca pacchetti tramite parole chiave:
    dnf search parola chiave

  - Visualizza i dettagli su un pacchetto:
   dnf info nome_pacchetto

  - Installa un nuovo pacchetto (usa `-y` per confermare automaticamente tutte le richieste):
    sudo dnf install nome_pacchetto

  - Rimuovere un pacchetto:
    sudo dnf remove nome_pacchetto

  - Elenca i pacchetti installati:
    dnf list --installed

  - Trova quali pacchetti forniscono un determinato file:
    dnf provides file

  - Visualizza tutte le operazioni passate:
    dnf history

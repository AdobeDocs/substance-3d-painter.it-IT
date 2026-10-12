---
source-git-commit: 6b6d52207ca1d043aaa1b2b14145b6b49d4c1942
workflow-type: tm+mt
source-wordcount: '155'
ht-degree: 0%
---
# Rimozione dei metadati HelpX legacy

Con Python 3.10 o versioni successive, eseguire i seguenti comandi dalla directory principale del repository:

```shell
python remove_helpx_metadta.py 1 <path>
python remove_helpx_metadta.py 2 <path>
```

La modalità `1` è un&#39;esecuzione a secco: elenca i file corrispondenti e segnala il numero di file
scansionati, file con corrispondenze e campi di metadati corrispondenti senza modificare i file.
La modalità `2` rimuove tali campi e segnala i conteggi delle rimozioni. Ometti `<path>` in
scansiona la cartella corrente. Tracciati di citazione contenenti spazi.

Lo script analizza in modo ricorsivo `.md` file (senza distinzione tra maiuscole e minuscole) e rimuove i file di primo livello
Campi di argomento iniziale YAML i cui nomi iniziano con `helpx`, inclusa la relativa riga multipla
valori. Conserva altri metadati, commenti, righe vuote, contenuti Markdown,
e le terminazioni di riga. Non rimuove `helpx` riferimenti nel corpo.
Controllare l&#39;esecuzione a secco prima di utilizzare la modalità `2`. La rimozione modifica i file in posizione senza
creazione di backup. Errori di file e problemi non chiusi vengono segnalati e vengono generati
uno stato di uscita diverso da zero. I file con argomento non chiuso vengono lasciati invariati.
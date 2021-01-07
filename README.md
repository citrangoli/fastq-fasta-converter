# FASTQ to FASTA converter
### Barbera Thomas 845538

Questo progetto consiste in un convertitore di file dal formato FASTQ al formato FASTA (con vincoli).

Il software è stato sviluppato tramite l'uso di Jupyter Notebook. Per poter eseguire il codice è quindi necessario aver installato il modulo `notebook`.
Viene inoltre richiesto il package `biopython`, usato per la lettura, scrittura e manipolazione di file di natura bioinformatica.

Gli input del programma devono essere indicati nella prima cella di codice. In particolare, oltre ai parametri L1, L2, Q1, Q2 e P, deve essere fornito un file di testo in formato FASTQ di cui deve essere fornito il nome nel notebook.

L'output del programma verrà salvato in un file di testo in formato FASTA. È possibile specificare il nome di tale file nel notebook.
L'output consiste in un insieme di reads che rispettano le condizioni date. Ogni read è composto da un header e da una sequenza. In particolare, nell'header sono indicati l'identificatore della sequenza, la sua lunghezza, la qualità minima delle sue basi, lo start e end (inclusi e 1-based) della sottoregione con qualità minima Q2 e la sua qualità media.

Assieme al codice sorgente, in questo repository è fornito un file di input di esempio con il relativo output.


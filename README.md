# Vite Hello!

Consegna

Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" (scrivete quello che volete, l'importante è che capiate il funzionamento del sistema)

## Soluzione

### Creazione della cartella

- creazione della cartella tramite la powershell
- eseguire il comando 'npm create vite@latest'
- seguire le istruzioni (nome, vue, javascript...)
- aprire la nuova cartella e visualizzare vsc (code .)
- aprire il terminale
- fare il comando 'npm install' ('installa' quello che trova nel package.json (eventuali vue - bootstrap - axios))
- fare il comando 'npm dev run' (è il nuovo live server)

### Creazione della pagina

- dentro src trovo ciò che serve
- in components creare i vari componenti del file
- usare 'export default' altrimenti non funziona
- richiamare tramite 'import' il componente e salvarlo in components (sotto data())
- richiamare il componente nel template

NB

nello script val js (con vue se inizializzato)
in template va l' html
nello style va il css (scoped rende lo style unico per quel componente)

# Descrizione del progetto
## Materiale Utilizzato:
- Arduino
- LCD
- Sensore Temperatura (DHT22)
- Ventola
- Riscaldatore (Resistenza)
- LED (Possibilmente RGB)
- 
<hr>

## Formato Dati:
- Attraverso la seriale arrivano i dati della ricetta, formattati in JSON
- L'Arduino scriverà in seriale quando la ricetta è stata completata, oppure se c'è un errore o è in lavorazione (sempre utilizzando JSON come formato)

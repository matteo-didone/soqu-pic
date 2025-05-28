# Descrizione del progetto
Simulazione lato Microcontrollore della simulazione d'esame. Richiesta: controllare il funzionamento delle autoclavi rispettando i parametri ricevuti.
Il microcontrollore deve:
- Decodificare i parametri della ricetta ricevuti tramite seriale
- Impostare il setpoint della temperatura
- Mantenere costante la temperatura dell'autoclave attraverso un sensore di temperatura, una ventola ed un riscaldatore
- Segnalare sul display LCD la pressione ed il controllo "enable_stirrers"
- Visualizzare sul display il tempo di funzionamento ("duration_in_hours")

<hr>

### Materiale Utilizzato:
- Arduino
- LCD
- Sensore Temperatura (DHT22)
- Ventola
- Riscaldatore (Resistenza)
- LED (Possibilmente RGB)

<hr>

### Formato Dati:
- Attraverso la seriale arrivano i dati della ricetta, formattati in JSON
- L'Arduino scriverà in seriale quando la ricetta è stata completata, oppure se c'è un errore o è in lavorazione (sempre utilizzando JSON come formato)

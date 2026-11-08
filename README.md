# Ritiri Demo

Versione demo pubblica della pianificazione giornaliera dei ritiri.

- **Dati fittizi:** il seed contiene solo nomi, indirizzi e numeri inventati.
- **CSV reale:** importalo dal telefono in *Impostazioni → Importa CSV*. Resta nel browser del dispositivo e non viene caricato su GitHub.
- **Offline:** dopo il primo caricamento il service worker mette in cache l'app. Su iPhone/iPad conviene aggiungerla alla schermata Home.
- **Mappe:** il pulsante *Apri in Maps* apre Apple Maps su iPhone/iPad e Google Maps altrove. Le statistiche mostrano i km tra le tappe e il totale stimato.
- **Backup:** usa *Salva stato (.json)*; non committare mai backup con dati reali.
- **Privacy:** nessun dato viene inviato a server esterni, eccetto gli indirizzi a Nominatim, le coordinate a OSRM e l'indirizzo al servizio mappe quando tocchi *Apri in Maps*. Sono dati fittizi.

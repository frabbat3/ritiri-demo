# Ritiri Demo

Versione demo pubblica della pianificazione giornaliera dei ritiri.

- **Dati fittizi:** il seed contiene solo nomi, indirizzi e numeri inventati.
- **CSV reale:** importalo dal telefono in *Impostazioni → Importa CSV*. Resta nel browser del dispositivo e non viene caricato su GitHub.
- **Offline:** dopo il primo caricamento il service worker mette in cache l'app. Su iPhone/iPad conviene aggiungerla alla schermata Home.
- **Backup:** usa *Salva stato (.json)*; non committare mai backup con dati reali.
- **Privacy:** nessun dato viene inviato a server esterni, eccetto gli indirizzi a Nominatim e le coordinate a OSRM per geocodifica e distanze. Sono dati fittizi.

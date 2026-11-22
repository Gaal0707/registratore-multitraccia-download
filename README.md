# Registratore Multitraccia — download

Programma per registrare chitarre e basso sopra le basi MP3 (con schede audio come Focusrite Scarlett, multieffetti come Ampero o Spark, ecc.):
take multiple, loop, marcatori, accordatore, riconoscimento di tonalità e accordi, trasposizione,
schema degli accordi e separazione della canzone nei singoli strumenti.

Scarica i file dalla pagina **[Ultima versione](../../releases/latest)** (sezione *Assets*).

## Windows 10/11

1. Scarica `Registratore-Multitraccia-Setup-x.y.z.exe` e avvialo.
2. Se compare "Windows ha protetto il PC": **Ulteriori informazioni → Esegui comunque** (il programma non ha una firma digitale a pagamento).
3. Segui l'installazione: non servono permessi di amministratore.

In alternativa c'è la versione **Portable** (`Registratore-Multitraccia-Portable-x.y.z.exe`), che si avvia senza installazione (ma va aggiornata a mano).

## Mac

1. Scegli il file giusto per il tuo Mac ( → *Informazioni su questo Mac*):
   - **Chip Apple** (M1, M2, M3, M4…): `Registratore-Multitraccia-x.y.z-mac-arm64.dmg`
   - **Processore Intel**: `Registratore-Multitraccia-x.y.z-mac-x64.dmg`
2. Apri il file `.dmg` e trascina **Registratore Multitraccia** nella cartella **Applicazioni**.
3. Primo avvio: il programma non ha la firma Apple a pagamento, quindi macOS lo blocca.
   - Apri **Impostazioni di Sistema → Privacy e sicurezza**, scorri in basso e premi **Apri comunque** accanto a "Registratore Multitraccia", poi conferma.
   - (Su macOS meno recenti: clic destro sull'app in Applicazioni → **Apri** → **Apri**.)
   - Se macOS dice che l'app "è danneggiata", apri il Terminale e scrivi:
     `xattr -dr com.apple.quarantine "/Applications/Registratore Multitraccia.app"`
4. Quando richiesto, consenti l'accesso al **microfono** (serve per la scheda audio).

## Aggiornamenti

All'apertura il programma controlla se c'è una versione nuova e propone **"Aggiorna ora"**:
su Windows si aggiorna e si riapre da solo; su Mac scarica la nuova versione e apre la finestra di installazione
(trascina di nuovo l'app in Applicazioni e scegli **Sostituisci**). Progetti e impostazioni restano.

## Note

- Alla prima separazione degli strumenti il programma scarica il motore di separazione (circa 1 GB, una sola volta).
- La latenza della scheda audio va calibrata su ogni computer e per ogni scheda (pulsante **Calibra**).
- Uso personale. La separazione degli strumenti usa il modello open source Demucs (Meta, licenza MIT).

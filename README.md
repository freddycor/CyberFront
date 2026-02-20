# CyberFront
FPS Multiplayer 100% replicato (UnrealEngine Blueprints)

## IMPORTANTE
I commit che sono segnati come "co-authored" sono stati creati a seguito di uno sviluppo condiviso, utilizzando il plugin "Multi User Editing" (plugin non consigliato).

##
- **Lingue:** Italiano, English
- **Modalità:** Deathmatch, FFA
- **Mappe:** Containers, Desert Castle, Stylized Egypt
- **Armi:** M4, AK-47, AK-74U, AS-VAL, Cecchino
- **Skin armi:** Normale, Galaxy, Holo

## Funzionalità
### Menu
- Autenticazione del giocatore tramite PlayFab (richiesta per giocare)
- Menu impostazioni (volumi divisi per categoria, risoluzione, preset grafico ecc.) (sia nel menù principale, che in game con il tasto ESC)
- Cambio lingua dell'intero gioco (Italiano, English)
- Sistema di host della partita
- Ricerca delle partite locali
- Join in una partita tramite IP
- Selezione della mappa (Containers, DesertCastle, Stylized Egypt)
- Selezione della modalità (Deathmatch, FFA)
- Selezione delle impostazioni di gioco (punti per vincere, vita dei giocatori)
- Funzionalità di kick dalla lobby, per l'host
- Sistema di pronto/non pronto, per iniziare la partita


### Partita
- Sistema di modalità modulare tramite game handler (Deathmatch e FFA) facilmente estendibile
- Posizione spawnpoints diversa per ogni mappa, modalità e team
- HUD dinamico in base alla modalità
- Animazioni custom per il movimento (walk, run, crouch, prone, ricarica, switch arma, reazione ad un colpo, morte)
- Statistiche differenti per ogni arma (danno, cadenza di fuoco, tempo di ricarica, munizioni, forza rinculo, parametri di riscaldamento)
- Sistema di classi per le armi con menù dedicato, visulizzazione delle statistiche di ogni arma e cambio della skin in gioco con posizione di preview per ogni mappa
- Suoni differenti per ogni arma
- Rinculo procedurale
- Respawn screen con animazione e info del killer
- Scoreboard in game con calcolo della classifica (tasto TAB)
- Schermata di fine partita con riepilogo
- HitMarker animato visivo e sonoro
- Calcolo del miglior spawnpoint in base alla posizione di tutti i giocatori vivi
- Blood screen quando si ha poca vita
- Sistema di rigenerazione della vita
- Suoni dei passi


 ### Shooting
- Proiettili reali con simulazione della gravità
- Effetto e suono di impatto del proiettile, diverso per superficie di impatto
- Sibilio del proiettile, se passato vicino al player
- Sistema avanzato di suoni per gestire colpi singoli/raffiche
- Distorsione visiva dovuta al calore della canna dell'arma, se utilizzata per raffiche ravvicinate
- Muzzle flash
- Sanguinamento all'impatto del proiettile
- Moltiplicatore del danno in base alla distanza e alla parte del corpo colpita

# Assets
**Gli assets sono tutti nella cartella "/Content/Assets" non versionati, importarli e spostarli tutti li per poterli utilizzare**

- Modelli Armi: https://www.fab.com/listings/8aeb9c48-b404-4dcd-9e56-1d0ecedba7f5
- Mappa Stylized Egypt: https://www.fab.com/listings/c935ca3e-dbb1-4b7d-a080-65de129c60bd
- Props pack: https://fab.com/s/e183defdb46b
- Container: https://fab.com/s/d0233cbfd13a
- Materiale Asfalto: https://fab.com/s/c4fbeada5f87
- Mappa Desert Castle: https://fab.com/s/7d840c42019b
- Suoni dei passi: https://fab.com/s/4abaf76a89a0

## Statistiche
- Tempo di realizzazione: troppo (circa 350 ore di lavoro complessive)
- Crash di Unreal Engine per i più disparati motivi: proprio troppi (almeno 15 al giorno) (non usate MultiUser Editing plugin)
- Vita sociale: 0
- Inveimenti: 10k+

<img width="781" height="588" alt="image" src="https://github.com/user-attachments/assets/56c09d5f-576b-40e6-9d6d-253d56e3da3e" />

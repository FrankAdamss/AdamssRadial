# AdamssRadial

**A radial brush menu for ZBrush.** Press a key and your favourite brushes appear in a circle under the cursor. Pick one with a flick and keep sculpting.

**[⬇ Download the latest version](https://github.com/FrankAdamss/AdamssRadial/releases/latest)**: get `AdamssRadial_Setup.exe` and run it.

*Italiano più sotto ↓*

---

## Features

- **Wheel at the cursor**: hold the hotkey, move towards a brush and release.
  - **Flick**: cross the edge of the wheel and the brush is picked right away.
  - **Tap**: tap the key quickly and the wheel stays open, then pick with a click.
- **Child brushes**: up to 3 per slot. They fan out when you hover the slot.
- **Preset alpha**: give a brush its own alpha. Picking the brush loads it and applies that alpha.
- **Several wheels**, each with its own hotkey and colour. A wheel can hold:
  - brushes (`.ZBP`, custom, VDM and IMM too);
  - tools (`.ZTL`);
  - ZBrush buttons (masking, Divide, DynaMesh, ZRemesher…);
  - keyboard shortcuts.
- **Floating library**: search all your brushes, with real thumbnails, favourites, recent brushes and a pin to keep it open over ZBrush.
- **Editor**: build your wheels by dragging brushes onto the slots.
- **One-click updates**: the app tells you when a new version is out.
- **English and Italian** interface.

## Requirements

- Windows 10 or 11 (macOS is not supported).
- ZBrush with ZScript plugin support. Tested on ZBrush 2022.0.8.

## Install

1. Close ZBrush.
2. Run `AdamssRadial_Setup.exe`.
   - If Windows says *"Windows protected your PC"*, click **More info › Run anyway**: the program is not digitally signed.
3. Pick your ZBrush versions and click **Install**.
   - The app installs in your user profile.
   - Windows asks for administrator rights only to copy the plugin into the ZBrush folder.
4. Start ZBrush: the plugin is in **ZPlugin › AdamssRadial**.

The AdamssRadial icon sits in the taskbar by the clock. Right-click it for the library, the editor, updates and *Start with Windows*.

## Default keys

They work only while ZBrush is in front.

| Key | Action |
|---|---|
| key under Esc (`` ` `` on US keyboards, `\` on Italian ones) | Brushes wheel |
| Shift + key under Esc | Tools wheel |
| Ctrl + key under Esc | Brush library |

You can change every hotkey in the editor. They also work from a Stream Deck, tablet buttons or F13–F24.

## Preset alpha

1. In the editor, right-click a brush.
2. Choose **Preset alpha…**.
3. Pick an alpha from the ZBrush ZAlphas gallery, or any PSD / PNG / JPG / BMP / TIF file.

## Updates

When a new version is published here, AdamssRadial shows a notice by the clock. Click **Update**: the app downloads the new version, checks it (SHA-256), updates itself and reopens. No administrator rights are needed, unless the new version also changes the plugin inside ZBrush.

## Other ZBrush versions

The plugin is compiled with ZBrush 2022.0.8. If it does not show up in ZPlugin in another version, recompile it there:

1. Copy `ZStartup\ZPlugs64\AdamssRadialData\AdamssRadial.txt` into `ZStartup\ZPlugs64`.
2. In ZBrush, use **ZScript › Load** on that file.
3. Delete the `.txt` and restart ZBrush.

## Uninstall

Windows **Settings › Apps › Installed apps › AdamssRadial › Uninstall**.

## Silent install (IT)

```
AdamssRadial_Setup.exe /S                        install into every ZBrush found
AdamssRadial_Setup.exe /S --root "D:\ZBrush 2022"   only into that folder
AdamssRadial_Setup.exe --uninstall /S            uninstall
```

---

# AdamssRadial (Italiano)

**Un menu radiale di pennelli per ZBrush.** Premi un tasto e i tuoi pennelli preferiti compaiono in cerchio sotto il cursore. Ne scegli uno con un gesto e continui a scolpire.

**[⬇ Scarica l'ultima versione](https://github.com/FrankAdamss/AdamssRadial/releases/latest)**: scarica `AdamssRadial_Setup.exe` e avvialo.

## Funzioni

- **Ruota al cursore**: tieni premuto l'hotkey, vai verso un pennello e rilascia.
  - **Flick**: superando il bordo della ruota il pennello si sceglie subito.
  - **Tocco**: con un tocco veloce del tasto la ruota resta aperta e scegli con un clic.
- **Pennelli figli**: fino a 3 per ogni posizione. Si aprono passando sopra lo slot.
- **Alpha preimpostata**: un pennello può avere la sua alpha. Quando lo scegli, ZBrush lo carica e applica quell'alpha.
- **Più ruote**, ognuna con hotkey e colore propri. Una ruota può contenere:
  - pennelli (`.ZBP`, anche custom, VDM e IMM);
  - tool (`.ZTL`);
  - bottoni di ZBrush (maschere, Divide, DynaMesh, ZRemesher…);
  - scorciatoie da tastiera.
- **Libreria fluttuante**: ricerca fra tutti i pennelli con miniature vere, preferiti, recenti e un pin per tenerla aperta sopra ZBrush.
- **Editor**: costruisci le ruote trascinando i pennelli sugli slot.
- **Aggiornamenti con un clic**: l'app ti avvisa quando esce una versione nuova.
- Interfaccia in **italiano e inglese**.

## Installazione

1. Chiudi ZBrush.
2. Avvia `AdamssRadial_Setup.exe`.
   - Se Windows mostra *"Windows ha protetto il PC"*, clicca **Ulteriori informazioni › Esegui comunque**: il programma non è firmato digitalmente.
3. Scegli le versioni di ZBrush e clicca **Installa**.
   - L'app si installa nel tuo profilo utente.
   - Windows chiede il permesso di amministratore solo per copiare il plugin nella cartella di ZBrush.
4. Avvia ZBrush: trovi il plugin in **ZPlugin › AdamssRadial**.

## Tasti predefiniti

Funzionano solo quando ZBrush è in primo piano.

| Tasto | Azione |
|---|---|
| tasto sotto Esc (`\` sulla tastiera italiana) | ruota Pennelli |
| Shift + tasto sotto Esc | ruota Strumenti |
| Ctrl + tasto sotto Esc | libreria pennelli |

## Alpha preimpostata

1. Nell'editor fai clic destro su un pennello.
2. Scegli **Alpha predefinita…**.
3. Prendi un'alpha dalla galleria ZAlphas oppure un file PSD / PNG / JPG / BMP / TIF.

## Aggiornamenti

Quando qui esce una versione nuova, AdamssRadial lo segnala vicino all'orologio. Clicca **Aggiorna**: l'app scarica la nuova versione, la verifica (SHA-256), si aggiorna e si riapre. Non servono permessi di amministratore, a meno che la nuova versione cambi anche il plugin dentro ZBrush.

## Disinstallazione

**Impostazioni di Windows › App › App installate › AdamssRadial › Disinstalla**.

* * *

title: "Troubleshooting" permalink: /troubleshooting.html lang: en_US ref: troubleshooting

* * *

Se non riesci ad avviare il tuo 3DS, controlla la sezione rilevante per il tuo problema e segui le istruzioni indicate. Una volta trovata una soluzione, potrai riprendere con la guida principale (Questa sezione è particolarmente lunga, prova a cercare il tuo problema utilizzando Ctrl+F.) {: .notice--primary}

**Se non riesci comunque a risolvere il tuo problema e hai bisogno di supporto, incolla il contenuto dei file .log relativi al tuo problema o alla parte della guida a cui sei arrivato dalla root della tua scheda SD in [Gist](https://gist.github.com/), poi prima di chiedere aiuto prepara una descrizione dettagliata del tuo problema e cosa hai tentato per risolverlo.** {: .notice--info}

## <a name="twl_broken" />Software DS / DSi non funzionante dopo aver completato la guida

#### Requisiti

* Il file TWL_FIRM `.cia` della tua console 
    * [`New_3DS TWL_FIRM - v9936.cia`](magnet:?xt=urn:btih:eab8558c97b18b1f329a2bfcc3c899b84c082a27&dn=New%5F3DS%20TWL%5FFIRM%20-%20v9936.cia&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=http%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969%2Fannounce&tr=http%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker1.wasabii.com.tw%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.baravik.org%3A6970%2Fannounce&tr=http%3A%2F%2Ftracker.tfile.me%2Fannounce&tr=udp%3A%2F%2Ftorrent.gresille.org%3A80%2Fannounce&tr=http%3A%2F%2Ftorrent.gresille.org%2Fannounce&tr=udp%3A%2F%2Ftracker.yoshi210.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filetracker.pl%3A8089%2Fannounce)
    * [`Old_3DS TWL_FIRM - v8817.cia`](magnet:?xt=urn:btih:17511eadb6e6f3ff22d04f90644e37bd2d96ca43&dn=Old%5F3DS%20TWL%5FFIRM%20-%20v8817.cia&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=http%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969%2Fannounce&tr=http%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker1.wasabii.com.tw%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.baravik.org%3A6970%2Fannounce&tr=http%3A%2F%2Ftracker.tfile.me%2Fannounce&tr=udp%3A%2F%2Ftorrent.gresille.org%3A80%2Fannounce&tr=http%3A%2F%2Ftorrent.gresille.org%2Fannounce&tr=udp%3A%2F%2Ftracker.yoshi210.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filetracker.pl%3A8089%2Fannounce)
* [`TWL Version Data - v0.cia`](magnet:?xt=urn:btih:4a106681407fede5de95cc8bda635432481f6b5d&dn=TWL%20Version%20Data%20-%20v0.cia&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=http%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969%2Fannounce&tr=http%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker1.wasabii.com.tw%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.baravik.org%3A6970%2Fannounce&tr=http%3A%2F%2Ftracker.tfile.me%2Fannounce&tr=udp%3A%2F%2Ftorrent.gresille.org%3A80%2Fannounce&tr=http%3A%2F%2Ftorrent.gresille.org%2Fannounce&tr=udp%3A%2F%2Ftracker.yoshi210.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filetracker.pl%3A8089%2Fannounce)
* [`DS Internet - v2048.cia`](magnet:?xt=urn:btih:2b9df8496922f2546dfb0b01220068ce53c19d3d&dn=DS%20Internet%20-%20v2048.cia&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=http%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969%2Fannounce&tr=http%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker1.wasabii.com.tw%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.baravik.org%3A6970%2Fannounce&tr=http%3A%2F%2Ftracker.tfile.me%2Fannounce&tr=udp%3A%2F%2Ftorrent.gresille.org%3A80%2Fannounce&tr=http%3A%2F%2Ftorrent.gresille.org%2Fannounce&tr=udp%3A%2F%2Ftracker.yoshi210.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filetracker.pl%3A8089%2Fannounce)
* [`DS Download Play - v1024.cia`](magnet:?xt=urn:btih:b581d3c5d98f5e621fddfc1ce5704bb45bf05a8c&dn=DS%20Download%20Play%20-%20v1024.cia&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=http%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969%2Fannounce&tr=http%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker1.wasabii.com.tw%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.baravik.org%3A6970%2Fannounce&tr=http%3A%2F%2Ftracker.tfile.me%2Fannounce&tr=udp%3A%2F%2Ftorrent.gresille.org%3A80%2Fannounce&tr=http%3A%2F%2Ftorrent.gresille.org%2Fannounce&tr=udp%3A%2F%2Ftracker.yoshi210.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filetracker.pl%3A8089%2Fannounce)
* [`Nintendo DS Cart Whitelist - v11264.cia`](magnet:?xt=urn:btih:7b90d506ad032a581a00035616eaa17a68c48eff&dn=Nintendo%20DS%20Cart%20Whitelist%20-%20v11264.cia&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=http%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce&tr=udp%3A%2F%2Fzer0day.ch%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969%2Fannounce&tr=http%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2Fexplodie.org%3A6969%2Fannounce&tr=udp%3A%2F%2F9.rarbg.com%3A2710%2Fannounce&tr=udp%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=http%3A%2F%2Fp4p.arenabg.com%3A1337%2Fannounce&tr=udp%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker.aletorrenty.pl%3A2710%2Fannounce&tr=http%3A%2F%2Ftracker1.wasabii.com.tw%3A6969%2Fannounce&tr=http%3A%2F%2Ftracker.baravik.org%3A6970%2Fannounce&tr=http%3A%2F%2Ftracker.tfile.me%2Fannounce&tr=udp%3A%2F%2Ftorrent.gresille.org%3A80%2Fannounce&tr=http%3A%2F%2Ftorrent.gresille.org%2Fannounce&tr=udp%3A%2F%2Ftracker.yoshi210.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.tiny-vps.com%3A6969%2Fannounce&tr=udp%3A%2F%2Ftracker.filetracker.pl%3A8089%2Fannounce)

#### Istruzioni

##### Sezione I - Preparazione

  1. Se assente, crea una cartella chiamata `cias` nella root della tua scheda SD
  2. Copia il file `TWL Version Data - v0.cia` nella cartella `/cias/` della tua scheda SD
  3. Copia il file `DS Download Play - v1024.cia` nella cartella `/cias/` della tua scheda SD
  4. Copia il file `DS Internet - v2048.cia` nella cartella `/cias/` della tua scheda SD
  5. Copia il file `Nintendo DS Cart Whitelist - v11264.cia` nella cartella `/cias/` della tua scheda SD
  6. Copia il file corretto per la tua console tra `New_3DS TWL_FIRM - v9936.cia` e `Old_3DS TWL_FIRM - v8817.cia` nella cartella `/cias/` della tua scheda SD

##### Sezione II - Installazione dei titoli

  1. Apri FBI
  2. Seleziona "SD"
  3. Seleziona "cias"
  4. Seleziona "\<current directory>"
  5. Seleziona "Install and delete all CIAs"
  6. Esci con il pulsante HOME

## <a name="rm_nnid" />Rimuovere un NNID senza formattare la console

#### Requisiti

* L'ultima versione di [GodMode9](https://github.com/d0k3/GodMode9/releases/)

#### Istruzioni

  1. Copia il file `GodMode9.bin` dal file `.zip` di GodMode9 nella cartella `/luma/payloads/` della tua scheda SD e rinomina il file `GodMode9.bin` in `/luma/payloads/` in `up_GodMode9.bin`
  2. Avvia la console tenendo premuto (Su) per avviare GodMode9 tramite l'arm9loaderhax
  3. Naviga fino a `SYSNAND CTRNAND` -> `data` -> (ID a 32 caratteri) -> `sysdata` -> `00010038`
  4. Tenendo premuto il pulsante (R), premi (X) mentre `00000000` è selezionato per rinominarlo
  5. Premi (Su) una volta per cambiare il nome in `10000000`
  6. Premi (A) per salvare la modifica
  7. Premi (A) per sbloccare la scrittura della SysNAND, quindi premi i pulsanti richiesti
  8. Ritorna al menu principale
  9. Premi (Start) per riavviare la console

## <a name="gw_fbi" />Impossibile iniettare "Informazioni per la salute e sicurezza" su una console downgradata tramite Gateway

Questo problema è causato dalla pessima implementazione da parte di Gateway di una procedura di downgrade, che duplica ogni applicazione installata nel sistema. Una di queste copie rimane inutilizzata, ma è abbastanza per confondere Decrypt9 e impedirgli di modificare l'applicazione corretta.

#### Requisiti

* L'ultima versione di [GodMode9](https://github.com/d0k3/GodMode9/releases/)

#### Istruzioni

  1. Copia il file `GodMode9.bin` dal file `.zip` di GodMode9 nella cartella `/luma/payloads/` della tua scheda SD e rinomina il file `GodMode9.bin` in `/luma/payloads/` in `up_GodMode9.bin`
  2. Reinserisci la tua scheda SD nel tuo 3DS
  3. Apri GodMode9 dall'arm9loaderhax tenendo premuto (Su) all'avvio 
  4. Naviga fino a `SYSNAND CTRNAND` -> `title` -> `00040010`
  5. Naviga fino alla cartella corretta per la tua console e per la tua regione: 
    * **Old 3DS EUR**: `00022300` -> `content`
    * **Old 3DS JPN**: `00020300` -> `content`
    * **Old 3DS USA**: `00021300` -> `content`
    * **New 3DS EUR**: `20022300` -> `content`
    * **New 3DS JPN**: `20020300` -> `content`
    * **New 3DS USA**: `20021300` -> `content`
  6. Noterai che ci sono due serie di file app e tmd, una con estensione in uppercase (`.TMD` and `.APP`), e una con estensione in lowercase (`.tmd` and `.app`)
  7. Tenendo premuto il pulsante (R), premi (Y) per creare una nuova cartella
  8. Premi (A) per confermare il nome `newdir` (non ha importanza)
  9. Premi (A) per sbloccare la scrittura della SysNAND, quindi premi i pulsanti richiesti
 10. Premi il pulsante (L) su ogni file con estensione in uppercase (`.TMD` and `.APP`) per evidenziarli
 11. Premi (Y) per copiare i file
 12. Naviga fino a `newdir`
 13. Premi (Y) per incollare i file
 14. Seleziona "Move path(s)"
 15. I file con estensione in uppercase sono ora stati spostati nella cartella `newdir`
 16. Premi (Start) per riavviare la console
 17. Ritorna a [Installare l'arm9loaderhax](installing-arm9loaderhax) e ri-esegui la sezione "Inject di FBI"
 18. Se ancora non dovesse funzionare, riporta i file con estensione in uppercase nella cartella `content`, poi muovi i file con estensione in lowercase nella cartella `newdir`, quindi ritorna a [Installare l'arm9loaderhax](installing-arm9loaderhax) e ri-esegui la sezione "Inject di FBI"

## <a name="ts_browser" />A browser based exploit is not working

Browser based exploits (such as browserhax or 2xrsa) are often unstable and crash frequently, but they can sometimes be fixed by doing the following steps

  1. Open the browser, then open the browser settings 
      1. Scroll to the bottom and Initialize Savedata (it also may be called Clear All Save Data)
      2. Try the exploit again

## <a name="ts_safe_a9lh" />System boots directly SafeA9LHInstaller

You copied the wrong `arm9loaderhax.bin` file to your SD card (you were only supposed to copy the `3ds` folder and `SafeA9LHInstaller.dat` file from the SafeA9LHInstaller zip)

  1. Use the correct `arm9loaderhax.bin` 
      1. Copy `arm9loaderhax.bin` from the Luma3DS `.zip` to the root of your SD card
      2. Reboot holding select and continue

## <a name="ts_safe_a9lh_screen" />SafeA9LHInstaller shows a glitched screen

This happens occasionally, but the reason is unknown. The buttons will still work, but the screen will be glitched looking

  1. Follow instructions as normal 
      1. Press (Select) and arm9loaderhax will be installed
      2. The console will reboot 
        * If the console does not reboot, wait 10 seconds, then power off your 3DS by holding down the power button

## <a name="ts_steelhax" />After System Transfering steelhax, it crashes to a black screen on *the target 3DS*

This is because you selected the wrong version in the steelhax installer.

  1. Download the [otherapp payload](https://smealum.github.io/3ds/#otherapp) corresponding to **the target 3DS's** version 
    * Ignore the NFIRM being downgraded
    * Use the version displayed in settings
  2. Rename the otherapp payload to `steelhax_payload.bin`
  3. Copy it `steelhax_payload.bin` to the root of **the target 3DS's** SD Card 
    * Overwrite any existing files
  4. Hold (B) while launching **Steel Diver: Sub Wars**

## <a name="ts_dsiware" />After doing the DSiWare Downgrade, my hacked DSiWare does not work

  1. Reboot **the source 3DS** while holding Start to launch Hourglass9
  2. Go to SysNAND Backup/Restore and restore SysNAND from `NANDmin.bin` (the one made before the system transfer)
  3. If you don't see the game at all on **the target 3DS**, link the NNID you bought the game with to **the target 3DS** and redownload it 
    * You may have to delete the game from "Data Management" in the "System Settings" first
    * If **the target 3DS** is not the latest version, you may have to run ctr-httpwn to access the eShop
  4. On **the source 3DS**, do the the save (and `.app` if you are using the `.app` page) injection steps
  5. On **the source 3DS**, go to System Settings, "Data Management", "DSiWare", then copy your DSiWare game to your SD card
  6. Either put **the source 3DS**'s SD card in **the target 3DS**, or rename the `Nintendo 3DS` on **the target 3DS**'s SD card and copy the `Nintendo 3DS` folder from **the source 3DS**'s SD card to **the target 3DS**'s SD card
  7. On **the target 3DS**, go to System Settings, "Data Management", "DSiWare", then copy your DSiWare game to the system
  8. Return your SD cards to normal, then continue with the DSiWare Downgrade

## <a name="ts_d9_backup" />Decrypt9 or Hourglass9 won't restore / can't find my NAND backup

  1. Make sure you do not have any folder named "Decrypt9" on **the root** of your SD card
  2. Try checking your SD card for errors using [H2testw (Windows)](h2testw-(windows)), [F3 (Linux)](f3-(linux)), or [F3X (Mac)](f3x-(mac))
  3. Try backing up your SD card files, then formatting it and copying them back
  4. Try a different SD card

## <a name="ts_sys_down" />Black screen on SysNAND boot

  1. Try booting with your SD card out, and then reinserting it after booting. 
      1. Power off your 3DS by holding down the power button.
      2. Take out the SD card.
      3. Power on the 3DS.
      4. When the home menu appears, reinsert your SD card.
      5. If this worked, you should Clear Home Menu's extdata by navigating to the following folder on your SD card: `/Nintendo 3DS/(32 Character ID)/(32 Character ID)/extdata/00000000/` 
        * EUR Region: Delete `00000098`
        * JPN Region: Delete `00000082`
        * USA Region: Delete `0000008f`
        * KOR Region: Delete `000000A9`
  2. Try booting without any cartridges inserted (including flashcarts)
  3. If you have a hardmod and a NAND backup, flash the backup back to SysNAND.
  4. Try booting into recovery mode and updating your system.  
    *This probably will not work for an Old 3DS downgraded to 2.1.0*  
    **This will BRICK a New 3DS downgraded to 2.1.0** 
      1. Power off your 3DS by holding down the power button.
      2. Hold L+R+A+Up.
      3. Power on the 3DS.
      4. If you enter safe mode, update your 3DS *only if you have an entrypoint for the latest FW version and it is possible to downgrade from it* and attempt the downgrade again.
  5. Your 3DS may be bricked. For support, ask for help at [#3dshacks on Rizon IRC](https://www.reddit.com/r/3dshacks/wiki/irc) or [3DS Hacking on Discord](https://discord.gg/MWxPgEp).

## <a name="ts_sys_a9lh" />Black screen on SysNAND boot after installing arm9loaderhax

  1. Ensure you have a working payload. 
      1. Check for the existence of `arm9loaderhax.bin` in the root of your SD card.
  2. Try resetting Luma's config and fix options 
      1. Delete `/luma/config.bin` from your SD card
      2. Set your options when it boots
  3. Test booting Hourglass9 
      1. On Luma3DS, hold (Start) on boot
  4. Try deleting home menu's extdata 
      1. Clear Home Menu's extdata by navigating to the following folder on your SD card: `/Nintendo 3DS/(32 Character ID)/(32 Character ID)/extdata/00000000/` 
        * EUR Region: Delete `00000098`
        * JPN Region: Delete `00000082`
        * USA Region: Delete `0000008f`
        * KOR Region: Delete `000000A9`
  5. Try booting without any cartridges inserted (including flashcarts)
  6. If you previously downgraded with Gateway, ensure that you are using the latest Luma3DS version (v6.2.3 or higher, at the least)
  7. If your NAND is of a version between 3.0.0 and 4.5.0, do the following: 
    * Ensure that you are using the latest Luma3DS version (v6.6 or higher, at the least)
    * Download [this file](http://nus.cdn.c.shop.nintendowifi.net/ccs/download/0004013800000002/00000056) and rename it to `firmware.bin`
    * Download [this file](http://nus.cdn.c.shop.nintendowifi.net/ccs/download/0004013800000002/cetk)
    * Copy `firmware.bin` and `cetk` to the `/luma/` folder on your SD card
    * Delete both of these files after updating your 3DS
  8. Try following [9.2.0 ctrtransfer](9.2.0-ctrtransfer)
  9. Ask for help at [#3dshacks on Rizon IRC](https://www.reddit.com/r/3dshacks/wiki/irc) or [3DS Hacking on Discord](https://discord.gg/MWxPgEp).

## <a name="ts_sys_blue" />Blue screen on boot (bootrom error)

  1. Your 3DS is bricked
  2. You will need to get a [hardmod](https://gbatemp.net/threads/414498/) or repair / replace the device
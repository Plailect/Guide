* * *

title: "Decrypt9 (Browser)" permalink: /decrypt9-(browser).html lang: en_US ref: decrypt9-(browser)

* * *

La première chose que ce guide va faire est de vous obtenez l''exécution Decrypt9, qui est un outil qui nous permettra d'installer la version 2.1.0, qui contient une vulnérabilité qui est nécessaire pour poursuivre l'exploitation du système. {: .notice}

Si vous avez déjà une installation RedNAND, ce guide concerne exclusivement SysNAND et vous devez suivre toutes les instructions dans SysNAND ou par rapport à SysNAND. Notez que les termes EmuNAND et RedNAND font référence à des implémentations légèrement différentes [du même concept](http://3dbrew.org/wiki/NAND_Redirection). {: .notice--info}

#### Ce dont vous aurez besoin

* La dernière version de [Decrypt9WIP](https://github.com/d0k3/Decrypt9WIP/releases/)

#### Instructions

  1. Créez un dossier qui s'appellera `files9` sur la racine de votre carte SD si le dossier n'existe pas
  2. Copier `Launcher.dat` et `Decrypt9WIP.dat` de l'archive Decrypt9WIP.`zip` à la racine de votre carte SD
  3. Réinsérez votre carte SD dans votre 3DS
  4. Ouvrez le navigateur et allez sur l'une des URLs suivantes sur votre 3DS 
    * `https://dukesrg.github.io/?Decrypt9WIP.dat`
    * `http://go.gateway-3ds.com/`
    * `http://www.reboot.ms/3ds/load.html?Launcher.dat`
    * `http://dukesrg.dynu.net/3ds/rop?GW17567.dat&Launcher.dat`
    * Make sure to try each URL if the first one doesn't work (some versions cannot use the first one, and some versions cannot use the last three)
    * If you get an error, [follow this troubleshooting guide](troubleshooting#ts_browser)
  5. Si l'exploit succède, vous allez démarrer dans Decrypt9

Continuez vers [2.1.0 ctrtransfer](2.1.0-ctrtransfer). {: .notice--primary}
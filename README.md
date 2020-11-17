<img src="https://img.shields.io/badge/Versione-1.0-green"> <img src="https://img.shields.io/badge/Aggiornato-si-orange"> <a href="https://forum.hassiohelp.eu/d/503-package-cronotermostato"><img src="https://img.shields.io/badge/Forum-hassiohelp-blue"></a> <a href="https://www.buymeacoffee.com/mariocandida80"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" width="90" alt="Buy Me A Coffee"></a>
<br>

Se vi piace il mio lavoro, potete supportarmi su <a href="https://www.paypal.com/paypalme/mariocandida">Paypal</a> oppure <a href="https://www.buymeacoffee.com/mariocandida80">offrimi un caffè</a>.<br>
<p align="center"/> <b>Addon Telegram per cronotermostato.</b> <br> </p>

Questo package ha una serie di automazioni che permettono di comandare il totalmente cronotermostato tramite telegram. <br>
<p align="center"/><img src="https://github.com/mariocandida80/addon_telegram/blob/master/foto/pannello1.jpg" width="390"></p>

Per installarlo basterà aggiungere al file configuration.yaml la seguente riga:
automation old: !include_dir_merge_list automations
Successivamente dovrete creare una cartella allo stesso livello di configuration.yaml e chiamarla automations.
Riavviate Home Assistant.
Dopo il riavvio copiate il file addon_telegram.yaml nella cartella appena creata, andate in impostazioni, controlli del server, ricarica le automazioni.
Aprite il vostro bot telegram e digitato /termostato e si aprirà il pannello di controllo.

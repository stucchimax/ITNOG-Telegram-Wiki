---
title: IP-Geolocation
body_classes: 'title-center title-h1h2'
---

## Problematica geolocalizzazione IP

Dopo trasferimenti di indirizzi IP spesso i servizi di geolocalizzazione non si aggiornano automaticamente. In questo articolo documentiamo alcune procedure e manteniamo una lista di contatti per richiedere l'aggiornamento manuale di servizi italiani.


## Preparazione

* confermare che sul database del RIPE l'oggetto [inetnum](https://www.ripe.net/manage-ips-and-asns/db/support/documentation/ripe-database-documentation/rpsl-object-types/4-2-descriptions-of-primary-objects/4-2-4-description-of-the-inetnum-object) (quello principale, che copre l'intero prefisso) riporta correttamente `country: IT`
* opzionale invece sono i attributi language, geoloc come anche i geofeed (RFC8805)
* si consiglia di aspettare qualche giorno o settimana dopo la modifica su RIPE, per permettere ai servizi di geolocalizzazione di aggiornare i propri database automaticamente
* controllare le seguenti liste, facendo un check con ogni singolo provider e far richiesta di aggiornamento la dove necessario:
  * [The Brothers WISP Geo and VPN](https://thebrotherswisp.com/index.php/geo-and-vpn/)
  * [RIPE: list of geolocation providers](https://www.ripe.net/manage-ips-and-asns/db/tools/geolocation-in-the-ripe-database)
* anche qua si consiglia di aspettare un po per permettere ai content provider italiani di aggiornare i sistemi automaticamente
* dopodichè si passa ai content provider italiani, scopo principale di questa pagina

## Lista di content e service provider italiani

Per aggiungere o modificare un contatto su questa lista e' sufficiente inviare una *pull request* sul [repository GitHub](https://github.com/stucchimax/ITNOG-Telegram-Wiki/) che gestisce il sito. Si prega di mantenere l'ordine alfabetico per Organizzazione.

| Organizzazione | Check-URL | contatto (webform/email) |
|-|-|-|
| DAZN | n/a | TBD |
| Mediaset | [Canale 5 diretta](https://www.mediasetplay.mediaset.it/diretta/canale5_cC5) | TBD |
| RAI | [Raiplay RAI1 diretta](https://www.raiplay.it/dirette/rai1) | TBD |
| Sisal | n/a | TBD |


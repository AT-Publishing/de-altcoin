---
published: true
guest: false

date: 2017-11-07 20:12:00 +0700
update: 2017-11-07 20:16:00 +0700

author: https://twitter.com/tradingfanbois
author_name: tradingfanbois
author_twitter: '@tradingfanbois'

comments: false

stories: true
#note: 'User Guide'
genres: Blog

layout: forestry
tickers: false

title: "Hardware-Wallets und Bitcoin SegWit2x Hardfork: Ledger vs Trezor auf Deutsch"
description: "Bei allen Hardware-Wallets besitzt man die privaten Schlüssel in Form des Seeds, so dass man die SegWit2x-Coins erhält. Die Einlösungsprozedur ist jedoch unterschiedlich je nach Wallet."

permalink: /segwit2x-ledger-trezor/
english: segwit2x-ledger-trezor

image:
- "/editorial/keys.jpg"

image_alt:
- "Bei allen Hardware-Wallets besitzt man die privaten Schlüssel in Form des Seeds, so dass man die SegWit2x-Coins erhält. Die Einlösungsprozedur ist jedoch unterschiedlich je nach Wallet."
categories:
- basics
chart: []
tags: ["segwit2x", "bitcoin", "bitcoin fork", "trezor", "ledger"]
identifier: 'hwsegwit2x11072017'
---

Bitcoin ist wieder vor einer Hardfork - dieses Mal ist der Konsens, dass es kein Nicht-Ereignis wie die Bitcoin Gold Fork sein wird.

Für einige Händler ist eine Bitcoin Hardfork nur so eine Dividende - sie erhalten "kostenlose" Coins, die sie zu ihrem Vorrat hinzufügen können, um sie entweder zu tauschen, für BTC zu verkaufen oder auszuzahlen.

Die SegWit2x-Schöpfer bestehen jedoch darauf, dass 2x-Blockchain der neue Bitcoin sein wird und dass Legacy-Blockchain keine Zukunft hat - was bedeutet, dass sie keinen Wiedergabeschutz implementiert haben (Replay Protection). Keine Replay-Protection heißt Transaktionen, die über die 2x-Chain weitergeleitet werden, können auch auf der alten Bitcoin-Kette wiedergegeben werden. Im Edeffekt ist es schwieriger die zwei Chains zu teilen wenn man beide Chains unabhängig behalten will.

SegWit2x soll auf dem Bitcoin-Block 494784 eingeführt werden (um den 16. November herum).

## Ledger Wallet und SegWit2x

[Lies die volle Ankündigung von Ledger hier.](https://www.ledger.fr/2017/11/06/preparing-segwit2x-hard-fork/)

Ledger Wallet wird sowohl 1x- als auch 2x-Ketten unterstützen.

Von der generischsten Benutzerperspektive aus empfiehlt Ledger das neueste Firmware-Update herunterzuladen, um die Schnittstelle für die Blockchainteilung zu erhalten.

Man muss die Coins teilen nur wenn man sowohl in die 1x- als auch die 2x-Blockchain interessiert ist, und diese unabhängig voneinander bewerten will. Aufgrund des fehlenden Wiedergabeschutzes muss man die Coins in der von Ledger bereitgestellten Schnittstelle verarbeiten um eine Wiederholung der Transaktionen zu vermeiden.

Für die Aufteilung bietet Ledger Wallet zwei Möglichkeiten: Eine basiert auf einem Drittanbieter-Tool - die ist manuell -- und eine die Ledgers eigene ist. Die zweite Variante ist automatisiert. Die automatisierte Variante (verfügbar bei Ledger Nano S und Blau, aber nicht bei Ledger Nano) ist der bevorzugte Weg denn es ist auch für Anfänger geeignet.

Ledger nennt den automatischen Prozess *"Halbverwahrer"-Prozess*: Sie werden die Coins der Benutzer verderben, was innerhalb der Ledger-Architektur möglich ist, ohne dass die Benutzer den Zugriff auf ihre Schlüssel übergeben.

Ledger wird weitere Details näher an der Fork liefern.

**Wenn du noch keinen [Ledger Nano S](https://www.ledgerwallet.com/r/e274?path=/products/ledger-nano-s) hast, ist es wahrscheinlich schon zu spät einen für die SegWit2x-Fork zu kaufen. Du kannst immer noch [hier einen Ledger Nano S bestellen (zur Zeit sind sie auf Lager!)](https://www.ledgerwallet.com/r/e274?path=/products/ledger-nano-s), wahrscheinlich ist dies nicht die letzte Bitcoin-Fork.**

{{ site.ledger_728-90_animated }}

________

## Trezor Wallet und SegWit2x

[Lies die volle Ankündigung von SatoshiLabs hier.](https://blog.trezor.io/trezor-statement-segwit2x-2x-hard-fork-b2x-f245fe4f0fb)

[Trezor Wallet von SatoshiLabs](https://shop.trezor.io?a=fany@tutanota.com) wird sowohl 1x als auch 2x Blockchain unterstützen.

Wie bei Ledger, man muss die Bitcoins manuell aufteilen falls man beide Chains unabhängig voneinander nutzen will.

Dieser Vorgang wird bei Trezor nur manuell durchgeführt. SatoshiLabs werden implementieren ein für diese Fork spezifisches Splitting-Tool (d.h. ein Tool für eine Hardfork ohne Wiedergabeschutz).

SatoshiLabs verdeutlichen [in dem offiziellen Blogbeitrag](https://blog.trezor.io/trezor-statement-segwit2x-2x-hard-fork-b2x-f245fe4f0fb), dass die Blockchainteilung ohne Gewährleistungen geliefert wird - wenn etwas passiert mit deinen Coins, sind SatoshiLabs nicht verantwortlich.

SatoshiLabs werden [den Trezor-Blogbeitrag](https://blog.trezor.io/trezor-statement-segwit2x-2x-hard-fork-b2x-f245fe4f0fb) aktualisieren näher an der Fork - sobald das Splitting-Tool implementiert ist.

#### Zusammenfassung

*Du erhältst die Coins von der 2x-Blockchain sowie mit Ledger als auch mit Trezor. Es scheint wieder ein Gewinnpunkt für Ledger Wallet zu sein: Die Blockchainteilung Features die Ledger anbietet sind klar verständlich auch für die Laien, und Ledger machen es bekannt es gab einige Sicherheitsverbesserungsarbeiten.*

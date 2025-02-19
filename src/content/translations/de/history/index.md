---
title: Geschichte und Forks von Ethereum
description: Eine Geschichte der Ethereum-Blockchain, einschließlich der wichtigsten Meilensteine, Veröffentlichungen und Abspaltungen.
lang: de
sidebarDepth: 1
---

# Die Geschichte von Ethereum {#the-history-of-ethereum}

Ein Zeitstrang aller wichtigsten Meilensteine, Forks und Aktualisierungen der Ethereum-Blockchain.

<ExpandableCard title="Was sind Forks?" contentPreview="Changes to the rules of the Ethereum protocol which often include planned technical upgrades.">

Forks entstehen, wenn wichtige technische Neuerungen oder Änderungen am Netzwerk vorgenommen werden müssen. Sie stammen in der Regel von den [Ethereum-Verbesserungsvorschlägen (EIPs)](/eips) ab und verändern die "Richtlinien" des Protokolls.

Wenn für eine Standardsoftware eine Aktualisierung benötigt wird, veröffentlicht der Hersteller lediglich eine neue Version für den Endbenutzer. Blockchains arbeiten anders, da es keinen alleinigen Besitzer gibt. [Ethereum Anwendungen](/developers/docs/nodes-and-clients/) müssen die Software aktualisieren um neue Regeln zu implementieren. Plus Block Ersteller (Miner in einer Proof-of-Work Umgebung, Validatoren in einer Proof-of-Stake Umgebung) und Nodes erstellen neue Blöcke und müssen diese, entsprechend der neuen Richtlinien, validieren. [Mehr zu Konsensmechanismen](/Entwickler/Dokumente/Konsensmechanismen/)

Diese Regeländerungen können eine temporäre Teilung im Netzwerk erzeugen. Neue Blöcke konnen nach den neuen oder den alten Regeln erzeugt werden. Forks werden in der Regel im Voraus vereinbart, damit die Clients die Änderungen einheitlich übernehmen und der Fork mit den Upgrades zur Main Chain wird. In seltenen Fällen jedoch können Meinungsverschiedenheiten über Forks zu einer dauerhaften Spaltung des Netzwerks führen; am bekanntesten ist die Gründung von Ethereum Classic durch den [[DAO-Fork]](#dao-fork).

</ExpandableCard>

Suchst du nach weiteren Protokoll Verbesserungen? [Erfahre etwas über bevorstehende Upgrades von Ethereum](/upgrades/).

<Divider />

## 2022 {#2022}

### Gray Glacier {#gray-glacier}

<NetworkUpgradeSummary name="grayGlacier" />

#### Zusammenfassung {#gray-glacier-summary}

Das Gray Glacier Netzwerk-Upgrade hat die [Schwierigkeitsbombe](/glossary/#difficulty-bomb) um drei Monate nach hinten verschoben. Dies ist die einzige Änderung, die in diesem Upgrade eingeführt wurde, und ähnelt den [Arrow Glacier](#arrow-glacier) und [Muir Glacier](#muir-glacier) Upgrades. Ähnliche Änderungen wurden bei den Netzwerk-Upgrades [Byzantium](#byzantium),[Constantinople](#constantinople) und [London](#london) durchgeführt.

- [EF Blog - Gray Glacier Upgrade-Ankündigung](https://blog.ethereum.org/2022/06/16/gray-glacier-announcement/)

<ExpandableCard title="Gray Glacier EIPs" contentPreview="Official improvements included in this upgrade.">

- [EIP-5133](https://eips.ethereum.org/EIPS/eip-5133) – _verzögert die Schwierigkeitsbombe bis September 2022_

</ExpandableCard>

<Divider />

## 2021 {#2021}

### Arrow Glacier {#arrow-glacier}

<NetworkUpgradeSummary name="arrowGlacier" />

#### Zusammenfassung {#arrow-glacier-summary}

Das Arrow Glacier Netzwerk-Upgrade hat die [Schwierigkeitsbombe](/glossary/#difficulty-bomb) um mehrere Monate nach hinten geschoben. Dies ist die einzige Änderung, die mit diesem Upgrade eingeführt wird, und ähnelt dem [Muir Glacier](#muir-glacier)-Upgrade. Ähnliche Änderungen wurden bei den Netzwerk-Upgrades [Byzantium](#byzantium),[Constantinople](#constantinople) und [London](#london) durchgeführt.

- [EF Blog – Ankündigung des Arrow Glacier-Upgrades](https://blog.ethereum.org/2021/11/10/arrow-glacier-announcement/)
- [Ethereum Cat Herders – Ethereum Arrow Glacier-Upgrade](https://medium.com/ethereum-cat-herders/ethereum-arrow-glacier-upgrade-e8d20fa4c002)

<ExpandableCard title="Arrow Glacier EIPs" contentPreview="Official improvements included in this upgrade.">

- [EIP-4345](https://eips.ethereum.org/EIPS/eip-4345) – _Verschiebung der Schwierigkeitsbombe bis Juni 2022_

</ExpandableCard>

---

### Altair {#altair}

<NetworkUpgradeSummary name="altair" />

#### Zusammenfassung {#altair-summary}

Das Altair-Upgrade war das erste geplante Upgrade für die [Beacon Chain](/upgrades/beacon-chain). Es wurde als Unterstützung für „Sync-Komitees" hinzugefügt und somit das Aktivieren sogenannter „Light-Clients", die Inaktivität von Validatoren und die Reduzierung von Strafen bis hin zu ihren vollen Werten.

- [Lesen Sie die Altair-Upgrade-Spezifikation](https://github.com/ethereum/consensus-specs/tree/dev/specs/altair)

#### <Emoji text=":tada:" size={1} mr="0.5rem" />Fun Fact! {#altair-fun-fact}

Altair war das erste große Netzwerk-Upgrade, für das es einen genauen Einführungszeitpunkt gab. Jedes vorherige Upgrade basierte auf einer angegebenen Blocknummer auf der Proof-of-Work-Kette, bei der die Blockzeiten variieren. Die Beacon Chain erfordert kein Lösen von Proof-of-Work und arbeitet stattdessen mit einem zeitbasierten Epochensystem, das aus 32 zwölfsekündigen „Slots" besteht, in denen Validatoren Blöcke vorschlagen können. Deshalb wussten wir genau, wann wir Epoche 74.240 erreichen würden und Altair live gehen würde!

- [Beaconcha.in Glossar – Slots](https://kb.beaconcha.in/glossary#slots)

---

### London {#london}

<NetworkUpgradeSummary name="london" />

#### Zusammenfassung {#london-summary}

Das London-Upgrade führte die [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559) ein, die den Markt für Transaktionsgebühren reformierte sowie Änderungen bei der Handhabung von Gasrückerstattungen und dem [Ice-Age](/glossary/#ice-age)-Zeitplan beinhaltete.

- [Sind Sie ein DApp-Entwickler? Bitte aktualisieren Sie Ihre Bibliotheken und Werkzeuge.](https://github.com/ethereum/execution-specs/blob/master/network-upgrades/london-ecosystem-readiness.md)
- [Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2021/07/15/london-mainnet-announcement/)
- [Die Erklärung der Ethereum Cat Herder lesen](https://medium.com/ethereum-cat-herders/london-upgrade-overview-8eccb0041b41)

<ExpandableCard title="London EIPs" contentPreview="Official improvements included in this upgrade.">

- [EIP-1559](https://eips.ethereum.org/EIPS/eip-1559) – _verbessert den Markt für Transaktionsgebühren_
- [EIP-3198](https://eips.ethereum.org/EIPS/eip-3198) – _gibt die „BASEFEE" aus einem Block zurück_
- [EIP-3529](https://eips.ethereum.org/EIPS/eip-3529) - _reduziert die Gasrückerstattungen für den EVM-Betrieb_
- [EIP-3541](https://eips.ethereum.org/EIPS/eip-3541) - _verhindert die Bereitstellung von Verträgen, die mit „0xEF" beginnen_
- [EIP-3554](https://eips.ethereum.org/EIPS/eip-3554) – _verschiebt die Eiszeit auf Dezember 2021_

</ExpandableCard>

---

### Berlin {#berlin}

<NetworkUpgradeSummary name="berlin" />

#### Zusammenfassung {#berlin-summary}

Mit dem Berliner Upgrade wurden die Gaskosten für bestimmte EVM-Aktionen optimiert und die Unterstützung für mehrere Transaktionsarten erweitert.

- [Lies die Ankündigung der Ethereum Foundation](https://blog.ethereum.org/2021/03/08/ethereum-berlin-upgrade-announcement/)
- [Lies die Erklärung der Ethereum Cat Herder](https://medium.com/ethereum-cat-herders/the-berlin-upgrade-overview-2f7ad710eb80)

<ExpandableCard title="Berlin EIPs" contentPreview="Official improvements included in this upgrade.">

- [EIP-2565](https://eips.ethereum.org/EIPS/eip-2565) – _senkt ModExp-Gaskosten_
- [EIP-2718](https://eips.ethereum.org/EIPS/eip-2718) – _ermöglicht eine einfachere Unterstützung für mehrere Transaktionsarten_
- [EIP-2929](https://eips.ethereum.org/EIPS/eip-2929) – _Gaskostenerhöhungen für staatliche Zugangsopcodes_
- [EIP-2930](https://eips.ethereum.org/EIPS/eip-2930) – _fügt optionale Zugriffslisten hinzu_

</ExpandableCard>

<Divider />

## 2020 {#2020}

### Entstehungsgeschichte der Beacon Chain {#beacon-chain-genesis}

<NetworkUpgradeSummary name="beaconChainGenesis" />

#### Zusammenfassung {#beacon-chain-genesis-summary}

Die [Beacon Chain](/upgrades/beacon-chain/) benötigte zum sicheren Betrieb 16.384 Einzahlungen von 32 gestakten ETH. Dazu kam es am 27. November, was bedeutet, dass die Beacon Chain am 1. Dezember 2020 mit der Erzeugung von Blöcken begann. Dies ist ein wichtiger erster Schritt, um die [Vision von Ethereum](/roadmap/vision/) zu erreichen.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2020/11/27/eth2-quick-update-no-21/)

<DocLink to="/upgrades/beacon-chain/">
  Die Beacon Chain
</DocLink>

---

### Staking Einzahlungsvertrag auf Ethereum hochgeladen {#staking-deposit-contract}

<NetworkUpgradeSummary name="stakingDepositContractDeployed" />

#### Zusammenfassung {#deposit-contract-summary}

Mit dem Stakingeinzahlungsvertrag wurde [Staking](/glossary/#staking) im Ökosystem von Ethereum eingeführt. Obwohl es sich um einen [Mainnet](/glossary/#mainnet)-Vertrag handelt, hatte er einen direkten Einfluss auf den Zeitplan für die Einführung der [Beacon Chain](/upgrades/beacon-chain/), einem wichtigen [Ethereum-Upgrade](/upgrades/).

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2020/11/04/eth2-quick-update-no-19/)

<DocLink to="/staking/">
  Staking
</DocLink>

---

### Muir Glacier {#muir-glacier}

<NetworkUpgradeSummary name="muirGlacier" />

#### Zusammenfassung {#muir-glacier-summary}

Die Muir-Glacier-Abspaltung führte eine Verzögerung in die [Schwierigkeitsbombe](/glossary/#difficulty-bomb) ein. Erhöhungen der Blockschwierigkeitsstufe des [Proof-of-Work](/developers/docs/consensus-mechanisms/pow/) Konsensmechanismus drohte die Nutzbarkeit von Ethereum zu verringern, indem die Wartezeiten für das Senden von Transaktionen und die Verwendung von dApps erhöht werden.

- [Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2019/12/23/ethereum-muir-glacier-upgrade-announcement/)
- [Die Erklärung der Ethereum Cat Herder lesen](https://medium.com/ethereum-cat-herders/ethereum-muir-glacier-upgrade-89b8cea5a210)

<ExpandableCard title="Muir Glacier EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-2384](https://eips.ethereum.org/EIPS/eip-2384) – _verzögert die Schwierigkeitsbombe auf weitere 4.000.000 Blöcke, oder ~611 Tage._

</ExpandableCard>

<Divider />

## 2019 {#2019}

### Istanbul {#istanbul}

<NetworkUpgradeSummary name="istanbul" />

#### Zusammenfassung {#istanbul-summary}

Die Istanbul-Abspaltung:

- Optimierte [Gas-](/glossary/#gas) Kosten für bestimmte Aktionen in der [EVM](/developers/docs/ethereum-stack/#ethereum-virtual-machine).
- Verbesserte Denial-of-Service Angriffswiderstandskraft.
- Machte [Skalierungslösungen der Ebene 2](/developers/docs/scaling/#layer-2-scaling) basierend auf SNARKs und STARKs leistungsstärker.
- Aktivierte Ethereum und Zcash zur Interoperation.
- Erlaubte Verträge zur Einführung kreativerer Funktionen.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2019/11/20/ethereum-istanbul-upgrade-announcement/)

<ExpandableCard title="Istanbul EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-152](https://eips.ethereum.org/EIPS/eip-152) - _erlaubt Ethereum, mit datenschutzfreundlichen Währungen wie Zcash zu arbeiten._
- [EIP-1108](https://eips.ethereum.org/EIPS/eip-1108) - _billigere Kryptographie zur Verbesserung der [gas](/Glossar/#Gas) Kosten._
- [EIP-1344](https://eips.ethereum.org/EIPS/eip-1344) - _Schutz von Ethereum vor Replay-Angriffen durch Hinzufügen von „CHAINID" [opcode](/developers/docs/ethereum-stack/#ethereum-virtual-machine)._
- [EIP-1884](https://eips.ethereum.org/EIPS/eip-1884) - _Optimierung der Opcode-Gaspreise basierend auf dem Verbrauch._
- [EIP-2028](https://eips.ethereum.org/EIPS/eip-2028) - _verringert die Kosten für CallData, um mehr Daten in Blöcken zu ermöglichen - gut für [Layer 2 Skalierung](/developers/docs/scaling/#layer-2-scaling)._
- [EIP-2200](https://eips.ethereum.org/EIPS/eip-2200) - _andere Opcode-Gaspreis-Änderungen._

</ExpandableCard>

---

### Konstantinopel {#constantinople}

<NetworkUpgradeSummary name="constantinople" />

#### Zusammenfassung {#constantinople-summary}

Die Konstantinopel-Fork:

- Sie stellte sicher, dass die Blockchain nicht einfrieren konnte, bevor der [Proof-of-Stake](#beacon-chain-genesis) implementiert wurde.
- Optimierte die [Gas-](/glossary/#gas)-Kosten für bestimmte Aktionen in der [EVM](/developers/docs/ethereum-stack/#ethereum-virtual-machine).
- Fügte die Möglichkeit hinzu, mit Adressen zu interagieren, die noch nicht erstellt wurden.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2019/02/22/ethereum-constantinople-st-petersburg-upgrade-announcement/)

<ExpandableCard title="Konstantinopel-EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-145](https://eips.ethereum.org/EIPS/eip-145) – _optimiert Kosten bestimmter On-Chain-Aktionen._
- [EIP-1014](https://eips.ethereum.org/EIPS/eip-1014) – _gestattet Ihnen das Interagieren mit Adressen, die noch erstellt werden müssen._
- [EIP-1052](https://eips.ethereum.org/EIPS/eip-1052) – _optimiert die Kosten bestimmter On-Chain-Aktionen._
- [EIP-1234](https://eips.ethereum.org/EIPS/eip-1234) – _verhindert die Einfrieren der Blockchain vor dem Proof-of-Stake._

</ExpandableCard>

<Divider />

## 2017 {#2017}

### Byzantium {#byzantium}

<NetworkUpgradeSummary name="byzantium" />

#### Zusammenfassung {#byzantium-summary}

Die Byzantium-Fork:

- Reduzierte die Block-[Mining](/developers/docs/consensus-mechanisms/pow/mining/)-Belohnungen von 5 auf 3 ETH.
- Verzögerte die [Schwierigkeitsbombe](/glossary/#difficulty-bomb) um ein Jahr.
- Fügte die Möglichkeit hinzu, nicht zustandsverändernde Aufrufe zu anderen Verträgen zu tätigen.
- Hinzufügung bestimmter Kryptographie-Methoden, um [Layer-2-Skalierung](/developers/docs/scaling/#layer-2-scaling) zu ermöglichen.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2017/10/12/byzantium-hf-announcement/)

<ExpandableCard title="Byzantium-EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-140](https://eips.ethereum.org/EIPS/eip-140) - _ergänzt „REVERT„ Opcode._
- [EIP-658](https://eips.ethereum.org/EIPS/eip-658) - _Statusfeld zu Transaktionsbestätigungen hinzugefügt, um Erfolg oder Misserfolg anzuzeigen._
- [EIP-196](https://eips.ethereum.org/EIPS/eip-196) - _erweitert elliptische Kurve und skalare Multiplikation, um [ZK-Snarks](/developers/docs/scaling/zk-rollups/) zu ermöglichen._
- [EIP-197](https://eips.ethereum.org/EIPS/eip-197) - \_erweitert elliptische Kurve und Skalarmultiplikation, um [ZK-Snarks](/entwickler/docs/scaling/zk-rollups/) zu ermöglichen.
- [EIP-198](https://eips.ethereum.org/EIPS/eip-198) - _ermöglicht RSA-Signaturprüfung._
- [EIP-211](https://eips.ethereum.org/EIPS/eip-211) - _erweitert die Unterstützung für Rückgabewerte variabler Länge._
- [EIP-214](https://eips.ethereum.org/EIPS/eip-214) - _erweitert den „STATICCALL"-Opcode, der nicht zustandsverändernde Aufrufe zu anderen Verträgen erlaubt._
- [EIP-100](https://eips.ethereum.org/EIPS/eip-100) - _Ändert die Formel für die Schwierigkeitsanpassung._
- [EIP-649](https://eips.ethereum.org/EIPS/eip-649) - _verzögert [difficulty bomb](/glossary/#difficulty-bomb) um 1 Jahr und reduziert die Blockbelohnung von 5 auf 3 ETH._

</ExpandableCard>

<Divider />

## 2016 {#2016}

### Spurious Dragon {#spurious-dragon}

<NetworkUpgradeSummary name="spuriousDragon" />

#### Zusammenfassung {#spurious-dragon-summary}

Die Spurious-Dragon-Fork war die zweite Reaktion auf die Denial-of-Service (DoS) Angriffe auf das Netzwerk (September/Oktober 2016) einschließlich:

- Abstimmen der Opcode-Preise, um zukünftige Angriffe auf das Netzwerk zu verhindern.
- Aktivierung des „Debloat“ (Wachstumsveringerung) des Blockchain-Zustandes.
- Hinzufügen von Replay-Angriffsschutz.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2016/11/18/hard-fork-no-4-spurious-dragon/)

<ExpandableCard title="Spurious Dragon EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-155](https://eips.ethereum.org/EIPS/eip-155) – _verhindert, dass Transaktionen von einer Ethereum-Kette auf eine andere Kette übertragen werden, z. B. eine Testnet-Transaktion, die auf der Hauptkette von Ethereum wiedergegeben wird._
- [EIP-160](https://eips.ethereum.org/EIPS/eip-160) – _passt die Preise für den Opcode „EXP" an - erschwert die Verlangsamung des Netzes durch rechenintensive Vertragsoperationen._
- [EIP-161](https://eips.ethereum.org/EIPS/eip-161) – _ermöglicht die Entfernung von leeren Konten, die durch DOS-Angriffe hinzugefügt wurden._
- [EIP-170](https://eips.ethereum.org/EIPS/eip-170) – _ändert die maximale Codegröße, die ein Vertrag auf der Blockchain haben kann, auf 24576 Bytes._

</ExpandableCard>

---

### Tangerine Whistle {#tangerine-whistle}

<NetworkUpgradeSummary name="tangerineWhistle" />

#### Zusammenfassung {#tangerine-whistle-summary}

Die Tangerine-Whistle-Fork war die erste Reaktion auf die Denial-of-Service (DoS) Angriffe auf das Netzwerk (September/Oktober 2016) einschließlich:

- Lösung der dringenden Probleme im Bereich der Netzwerkgesundheit im Zusammenhang mit unterbewerteten Operationscodes.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2016/10/18/faq-upcoming-ethereum-hard-fork/)

<ExpandableCard title="Tangerine-Whistle-EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-150](https://eips.ethereum.org/EIPS/eip-150) – _erhöht die Gaskosten von Opcodes, die in Spam -Attacken benutzt werden können._
- [EIP-158](https://eips.ethereum.org/EIPS/eip-158) – _verringert die Zustandsgröße, indem eine große Anzahl leerer Konten erntfernt wird, die aufgrund von Fehlern in früheren Versionen des Ethereum-Protokolls zu sehr niedrigen Kosten in den Zustand gebracht wurden._

</ExpandableCard>

---

### DAO-Fork {#dao-fork}

<NetworkUpgradeSummary name="daoFork" />

#### Zusammenfassung {#dao-fork-summary}

Die DAO-Abspaltung war eine Reaktion auf den [DAO-Angriff 2016](https://www.coindesk.com/markets/2016/06/25/understanding-the-dao-attack/), bei dem einem unsicheren [DAO](/glossary/#dao)-Vertrag durch einen Hack über 3,6 Millionen ETH entzogen wurden. Die Fork verschiebt das Guthaben aus dem fehlerhaften Vertrag in einen [neuen Vertrag](https://etherscan.io/address/0xbf4ed7b27f1d666546e30d74d50d173d20bca754) mit einer einzigen Funktion: Abheben. Jeder, der Geld verloren hat, konnte 1 ETH für jeden 100 DAO-Token in seiner Wallet abheben.

Über diese Vorgehensweise wurde seitens der Ethereum-Community abgestimmt. Jeder ETH-Inhaber konnte über eine Transaktion auf [, einer Abstimmungsplattform,](http://v1.carbonvote.com/) abstimmen. Die Entscheidung zur Fork erreichte mehr als 85 % der Stimmen.

Einige Miner weigerten sich, die Abspaltung mitzutragen, da der Vorfall des DAO keinen Fehler im Protokoll darstellte. Sie gründeten [Ethereum Classic](https://ethereumclassic.org/).

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2016/07/20/hard-fork-completed/)

---

### Homestead {#homestead}

<NetworkUpgradeSummary name="homestead" />

#### Zusammenfassung {#homestead-summary}

Die Homestead-Abspaltung, die in die Zukunft schaute. Sie enthielt mehrere Protokolländerungen und eine Änderung des Netzwerks, die Ethereum die Möglichkeit gab, weitere Netzwerk-Upgrades durchzuführen.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2016/02/29/homestead-release/)

<ExpandableCard title="Homestead EIPs" contentPreview="Official improvements included in this fork.">

- [EIP-2](https://eips.ethereum.org/EIPS/eip-2) – _führt Änderungen am Prozess der Vertragserstellung durch._
- [EIP-7](https://eips.ethereum.org/EIPS/eip-7) – _fügt einen neuen Opcode hinzu: `DELEGATECALL`_
- [EIP-8](https://eips.ethereum.org/EIPS/eip-8) – _führt devp2p Forward-Kompatibilitätsanforderungen ein_

</ExpandableCard>

<Divider />

## 2015 {#2015}

### Frontier Thawing {#frontier-thawing}

<NetworkUpgradeSummary name="frontierThawing" />

#### Zusammenfassung {#frontier-thawing-summary}

Die Frontier-Thawing-Abspaltung hob das 5.000 [Gas](/glossary/#gas)-Limit pro [Block](/glossary/#block) auf und setzte den Standardgaspreis auf 51 [gwei](/glossary/#gwei). Dies erlaubte Transaktionen – Transaktionen benötigen 21.000 Gas. Die [Schwierigkeitsbombe](/glossary/#difficulty-bomb) wurde eingeführt, um eine zukünftige harte Abspaltung zu [Proof-of-Stake](/glossary/#pos) sicherzustellen.

- [Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2015/08/04/the-thawing-frontier/)
- [Lesen Sie das Ethereum Protokoll-Update 1](https://blog.ethereum.org/2015/08/04/ethereum-protocol-update-1/)

---

### Frontier {#frontier}

<NetworkUpgradeSummary name="frontier" />

#### Zusammenfassung {#frontier-summary}

Frontier war live, aber soweit nur die Implementierung eines grundsätzlichen Rahmens des Ethereum-Projekts. Es folgte der erfolgreichen olympischen Testphase. Es war für technische Benutzer gedacht, speziell für Entwickler. [Blöcke](/glossary/#block) hatten ein [Gas](/glossary/#gas)-Limit von 5.000. Diese Zeit des „Auftauens" ermöglichte es den Minern, ihren Betrieb zu starten und für Early-Adopters, ihre Kunden zu installieren, ohne dies „überstürzen“ zu müssen.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2015/07/22/frontier-is-coming-what-to-expect-and-how-to-prepare/)

<Divider />

## 2014 {#2014}

### Ether-Verkauf {#ether-sale}

<NetworkUpgradeSummary name="etherSale" />

Ether ging offiziell 42 Tage lang in den Verkauf. Man konnte es mit BTC kaufen.

[Die Ankündigung der Ethereum Foundation lesen](https://blog.ethereum.org/2014/07/22/launching-the-ether-sale/)

---

### Yellowpaper veröffentlicht {#yellowpaper}

<NetworkUpgradeSummary name="yellowpaperRelease" />

Das Yellowpaper, verfasst von Dr. Gavin Wood, ist eine technische Definition des Ethereum-Protokolls.

[Yellowpaper anzeigen](https://github.com/ethereum/yellowpaper)

<Divider />

## 2013 {#2013}

### Whitepaper veröffentlicht {#whitepaper}

<NetworkUpgradeSummary name="whitepaperRelease" />

Dieses einleitende Papier wurde ursprünglich 2013 von Vitalik Buterin, dem Gründer von Ethereum, vor dem Projektstart im Jahr 2015 veröffentlicht.

<DocLink to="/whitepaper/">
  Whitepaper
</DocLink>

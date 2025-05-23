---
title: "Fachinformatiker Prüfungsvorbereitung"
date: 2022-08-24T22:51:52-06:00
draft: false
type: docs
description: "Fachinformatiker Prüfungsvorbereitung ist eine Seite zur Prüfungsvorbereitung. Mit ihr kannst du dich Online auf die Fachinformatiker Prüfung vorbereiten."
---

## Ziel dieser Seite 🎯

Diese Seite hat das Ziel, das gesamte Prüfungswissen für die Fachinformatiker Berufe auf einer übersichtlichen Website darzustellen. Außerdem soll sie Open Source und von jedem erweiterbar sein. Gelöst wurde das ganze über GitHub. Wie genau du an diesem Projekt teilhaben kannst, wird im Unterpunkt [Contributing](./#contributing-) beschrieben. Der einfachste Punkt um zu dieser Seite beizutragen, ist aber sie bekannter zu machen. Wenn dir also gefällt, was wir hier erschaffen, dann erzähl es doch bitte allen Interessierten. Deine Berufsschulklasse oder Azubis im Betrieb werden sich sicher über ein bisschen Hilfe, bei der Prüfungsvorbereitung, freuen 😉

## Geschichte 👴

Als ich mich auf die Prüfung vorbereiten wollte, habe ich mir einige Notizen gemacht. Und genau aus diesen Notizen ging dann dieses Projekt hervor. Ich habe versucht so viel Wissen wie möglich zu sammeln und tue es auch nach wie vor. Die Website erhält deshalb auch regelmäßig neue Updates. Für die Zukunft erhoffe ich mir, dass an diesem Projekt so viele Fachinformatiker wie möglich teilhaben werden. Mithilfe von einigen Leuten kann so eine riesige Wissensdatenbank zur Prüfungsvorbereitung erstellt werden.

## Technische Details ⚙️

Fachinformatiker Prüfungsvorbereitung wurde mithilfe einiger Tools erstellt. Aber nicht alle davon musst du beherrschen, um daran Teil zu haben.

### Markdown ⬇️

Markdown ist der einzige wichtige Skill, den ihr wirklich benötigt, um an diesem Projekt teilhaben zu können. Aber keine Sorge, Markdown ist leicht zu erlernen 😉

Aber wozu genau wird denn jetzt Markdown benötigt?  
  
Der gesamte Content dieser Website ist in Markdown Dateien geschrieben. Diese werden zwar um ein paar Konfigurationseinstellungen ergänzt, aber der Content an sich ist in reinem Markdown geschrieben. Der Grund hierfür ist unter anderem die Möglichkeit der einfachen Zusammenarbeit mit einer großen Anzahl an möglichen Contributors.

### Hugo 🥂

Diese Markdown Dateien werden dann mit der Hilfe von Hugo, einem Static-Site-Generator, in eine Website konvertiert. Ein bisschen Wissen über Hugo würde zwar nicht schaden, aber das Erstellen von Content ist auch ganz einfach ohne dieses Wissen möglich. Für die Hugo Interessierten unter euch: Das Projekt benutzt das Docsy Theme, welches über Hugo Modules eingebunden wird.

### Docker 🐋

Docker wird komplett von mir verwaltet und um am Projekt teilzuhaben wird kein Wissen in diesem Bereich benötigt. Wer allerdings sich am Deployment und / oder an den Docker-Container beteiligen möchte, kann das natürlich gerne tun.  
Die Fachinformatiker Prüfungsvorbereitungs-Seite wird auf Basis eines Nginx Containers zu einem neuen Container gebaut. Dieser Container wird dann automatisch über GitHub Actions Pipelines auf Docker-Hub veröffentlicht.

## Contributing ✨

Wenn du Teil der Fachinformatiker Prüfungsvorbereitung Contributors werden möchtest, dann lese dir die [Contributing-Guidelines](https://github.com/LNA-DEV/Fachinformatiker-Pruefungsvorbereitung/blob/main/CONTRIBUTING.md) genauer durch ✨

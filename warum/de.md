# Warum?

Wir möchten digitale Selbstverteidigung stärken. Dieser ProxyStore ist Teil eines größeren Konzepts, das du [auf dys2p.com findest](https://dys2p.com/konzept.html).

## Risiken und Probleme beim Einkaufen im Internet

Onlineshopping ist bequem, unter den Aspekten der Privatsphäre und des Datenschutzes aber oft problematisch. Die meisten Onlineshops verlangen eine Vielzahl an Daten von dir. Häufig sollst du einen Account anlegen, mit dem deine Daten dauerhaft verknüpft werden. Doch auch ohne Account erhälst du meist standardmäßig eine Rechnung, und Rechnungsdaten müssen jahrelang gespeichert werden. Natürlich erfahren auch Zahlungsanbieter und Lieferdienste, wer du bist und wo du einkaufst.

**Leaks:** Es vergeht kein Tag, an dem nicht ein Onlineshop gehackt oder eine Kundendatenbank entwendet wird – sei es durch externe Akteure oder durch Insider. Einige dieser Datensammlungen landen öffentlich im Internet, andere kursieren nur in vertraulichen Kreisen.

**Überwachung:** Große Datenmengen wecken das Interesse staatlicher Behörden. Große Plattformen wie amazon besitzen Informationen über fast alle von uns. Für diese Daten interessieren sich auch Polizei und Geheimdienste. Du hast nichts zu verbergen? Die digitalen Begehrlichkeiten des Staates erzeugen ein Klima der Überwachung, das auch dich betrifft.

**Datenhandel und Werbung:** Auch nach Inkrafttreten der Datenschutz-Grundverordnung gehört die Weitergabe von Kundendaten im Internet oft zum Geschäftsmodell. Liest du immer das Kleingedruckte? Längst erhalten wir Werbung nicht mehr nur per E-Mail, Telefonanruf oder Post. Werbedienstleister versprechen, dich über verschiedene Webseiten hinweg identifizieren zu können ("tracking"), und die "Werbe-ID" vieler Smartphones unterstützt sie dabei. Während der Nutzen von Onlinewerbung umstritten ist, gelten Kundendatenbanken ganz klar als Vermögenswert. Wird eine Firma verkauft, fallen gewöhnlich auch die Kundendaten in neue Hände.

**Zahlung und Lieferung:** Ohne Kreditkarte oder PayPal-Account sind viele Dinge in der digitalen Welt unerreichbar. Mit neugierigen Mitbewohnern oder Nachbarinnen traust du dich vielleicht gar nicht, sie zu bestellen.

## Leaks – oops!

Veraltete Software im Einsatz, eine fehlerhafte Konfiguration, unachtsamer Umgang oder eine andere Ursache – und deine Daten sind plötzlich Personen zugänglich, für die sie nicht bestimmt waren. Oops. Je nach Akteur, deren Absichten und den betroffenen Daten können daraus unterschiedliche Aktionen zu deinem Nachteil folgen:

* Nutzung der Daten für wirtschaftliche Zwecke
  * Identitätsdiebstahl
  * Spam und Phishing
  * Erpressung & Reputationsschaden
* Nutzung der Daten für politische Zwecke, Spionage
* Stalking und Doxing

### Dreh- und Angelpunkt: E-Mail-Adressen

Die meisten Dienste identifizieren und kontaktieren dich über deine E-Mail-Adresse. Nur in manchen Fällen wird zusätzlich ein Nutzername verlangt. Deine E-Mail-Adresse lässt sich nicht nur für "Marketingzwecke" ([Spam](https://de.wikipedia.org/wiki/Spam)) und andere unerwünschte Kontaktaufnahmen verwenden, sondern auch für [Phishing](https://de.wikipedia.org/wiki/Phishing). Darüber hinaus können Angreifer versuchen, dein Passwort zu erraten. Falls sie mit "123456" oder dem Namen deines Haustieres keinen Erfolg haben, können sie weitere beliebte Passwörter oder Einträge aus einem Wörterbuch [durchprobieren](https://de.wikipedia.org/wiki/Brute-Force-Methode). Falls du das selbe Passwort woanders nutzt, kennen sie es vielleicht auch schon.

### Passwort-Hashes

Internetdienste speichern üblicherweise nicht den Klartext der Passwörter, sondern lediglich einen [Hashwert](https://de.wikipedia.org/wiki/Hashfunktion). Doch durch fehlerhafte Implementierungen oder anderweitig fahrlässiges Handeln der Betreiber können Passwörter auch im Klartext vorliegen. Mit der wachsenden Rechenleistung von Computern und fortschreitender kryptographischer Forschung steigen auch die Anforderungen an Hashfunktionen. Wird ein veraltetes Hashverfahren genutzt, können gespeicherte Hashwerte z. B. mit [Regenbogentabellen](https://de.wikipedia.org/wiki/Rainbow_Table) analysiert werden, um das genutzte Passwort im Klartext zu erhalten. Es gibt Dienstleister, die sich genau darauf spezialisiert haben.

### Zugriff auf Accounts und Informationen

Die Kombination aus einer E-Mail-Adresse und einem Klartext-Passwort (oder Abwandlungen davon) kann nicht nur bei dem E-Mail-Account selbst, sondern auch bei weiteren Diensten ausprobiert werden. Dieses [Credential Stuffing](https://web.archive.org/web/20201127094548/https://www.ionos.de/digitalguide/server/sicherheit/was-ist-credential-stuffing/) ist aus Angreifersicht relativ erfolgreich, da viele Personen bei verschiedenen Internetdiensten die gleichen Zugangsdaten verwenden. Nach einer erfolgreichen Anmeldung kann oft das Passwort geändert und der Account somit übernommen werden ([Account Hijacking](https://de.wikipedia.org/wiki/Hijacking)). Der Akteur bekommt nicht nur Zugriff auf gespeicherte Informationen, sondern kann auch weitere Informationen anfordern (z. B. gemäß des Auskunftsrechts der DSGVO) und im Namen der betroffenen Person Interaktionen vornehmen.

Nutzt [Passwortmanager](https://www.kuketz-blog.de/empfehlungsecke/#passwort-manager) mit einem zufallsgeneriertes Passwort für jeden Dienst. Falls es möglich ist, verwendet [Zwei-Faktor-Authentifizierung](https://de.wikipedia.org/wiki/Zwei-Faktor-Authentisierung) bzw. [Mehr-Faktor-Authentifizierung](https://en.wikipedia.org/wiki/Multi-factor_authentication), um Accounts besser abzusichern.

Gesammelte persönliche Informationen (z. B. Vor- und Nachname, Geschlecht, Geburtsdatum), Kontaktdaten (z. B. Telefonnummer, Liefer- und Rechnungsanschrift), Zahlungsdaten (z. B. Bankdaten, Kreditkarteninformationen), Plattformdaten (z. B. Anmeldedatum, IP-Adressen, Systeminformationen, Historie) und zusätzliche Nachweise wie beispielsweise eine Ausweiskopie oder die Ausweisnummer können auf vielfältige Weise missbräuchlich verwendet werden. Je mehr Informationen verfügbar sind, desto erfolgreicher können Angriffe sein.

### Fallbeispiel: Nutzung von Daten für wirtschaftliche Zwecke

Am 25. Juni 2020 konnte ein Akteur mehr als 1.075.000 E-Mail-Adressen und weitere Kundendaten zu über 272.000 Personen erlangen, darunter zusätzlich zur E-Mail-Adresse auch den Vor- und Nachnamen, eine Anschrift (Straße, Hausnummer, Postleitzahl, Ort und Land) und eine Telefonnummer. Das betroffene Unternehmen – Ledger – stellt Hardware-Wallets her, um Kryptowährungen zu sichern. Seitdem gibt es ein breites Spektrum an Aktionen zum Nachteil der Betroffenen.

Derartige Datensätze werden oft weiterverbreitet und von verschiedenen Akteure verwendet. Die Kundendaten von Ledger wurden für zahlreiche Phishing-Kampagnen in mehreren Sprachen und über diverse Kommuinkationswege (E-Mail, SMS) genutzt. Laut [Angaben der Firma](https://www.ledger.com/phishing-campaigns-status#phishing-campaigns) wurden seit dem 22. Oktober 2020 in diesem Zusammenhang 527 Phishing-Webseiten vom Netz genommen. Da der Datensatz auch Telefonnummern enthielt, konnten Akteure mittels [SIM-Swapping](https://de.wikipedia.org/wiki/SIM-Swapping) die oftmals für die Zwei-Faktor-Authentisierung genutzten Telefonnummern übernehmen und sich weiteren Zugang z. B. [auf Börsen für Kryptowährungen](https://web.archive.org/web/20210126113423/www.coindesk.com/ledger-leak-sim-swap-home-invasion-threats) verschaffen.

Ein erhöhtes Aufkommen von Phishing und Spam per E-Mail ist nach derartigen Vorfällen relativ normal. Was in diesem Fall hervorsticht ist, dass Kunden von Ledger mit [Einbrüchen](https://web.archive.org/web/20210126114520/https://www.reddit.com/r/ledgerwallet/comments/kh8q82/fantastic/), Entführung und dem Tod ([1](https://web.archive.org/web/20210126114848/https://www.reddit.com/r/ledgerwalletleak/comments/ki1nsz/received_phone_call_threatening_kidnapping_and/), [2](https://web.archive.org/web/20210126115052/https://www.reddit.com/r/CryptoCurrency/comments/kx9sy0/my_dad_just_received_a_death_threat_on_his/)) gedroht wird, um Geld zu erpressen.

Derartige Ereignisse sollten nicht isoliert betrachtet werden, sondern im Kontext weiterer Leaks und öffentlicher Informationen aus dem Netz. [Laut haveibeenpwned](https://web.archive.org/web/20201220212750/https://twitter.com/haveibeenpwned/status/1340770769106731008) waren 69% der E-Mail-Adressen bereits in vorherigen bekannten Leaks enthalten. Mit dem Dienst [haveibeenpwned](https://haveibeenpwned.com) können zahlreiche bekannte Datenleaks nach E-Mail-Adressen durchsucht werden.

### Fallbeispiel: Nutzung von Daten mit politischer Motivation

Wie man durch die Bestellung subkultureller Güter auf Todeslisten rechtsterroristischer Gruppierungen wie "Nordkreuz" landet, zeigt ein Sicherheitsvorfall beim "Impact Mailorder".

Am 20. Januar 2015 verschafften sich eine oder mehrere Personen die Kundendatenbank des Onlineversands "Impact Mailorder". Kurz darauf wurde ein Text mit dem Titel "impact-mailorder.de hacked by National Sozialistische Hacker Crew" auf pastebin.com veröffentlicht, der 108 Hakenkreuze, Links zum Download der Daten und einen Auszug von 250 Personendaten enthielt. Die Datenbank umfasst circa 40.000 Einträge mit Vornamen, Nachnamen, Straßen, Hausnummern, Postleitzahlen und Orten, Telefonnummern und E-Mail-Adressen der Kunden. Sie verbreitete sich in Neonazi-Kreisen schnell. Wenige Tage darauf, am 29. Januar 2015, erschien ein weiterer Text, wieder mit 108 Hakenkreuzen und Verweisen zum Download der Daten von weiteren circa 15.000 Personen.

Seitdem werden diese Daten komplett oder anteilig in rechten Kreisen weiterverbreitet, teilweise unter anderen Namen wie z. B. "Antifa-Liste" oder "Mitglieder der Antifa". Von einem Ableger der NPD-Jugendorganisation "JN", über [die AfD](https://web.archive.org/web/20201109025731/https://www.hz.de/meinort/heidenheim/merz-verbreitete-geklaute-adressen-31284866.html) bis hin zu rechtsextremen und rechtsterroristischen Gruppierungen wie ["Nordkreuz"](https://de.wikipedia.org/wiki/Nordkreuz), ["Revolution Chemnitz"](https://web.archive.org/web/20190711223234/https://www.tagesspiegel.de/politik/rechter-terror-revolution-chemnitz-hatte-zugriff-auf-24-300-daten-von-linken-und-punks/24578260.html) und dem ["Aryan Circle Germany"](https://de.wikipedia.org/wiki/Aryan_Circle_Germany) fand eine Verbreitung und Nutzung der Daten statt. "Nordkreuz" hat die Datensammlung um Informationen aus polizeilichen Datenbanken erweitert, um – laut protokollierter Aussage eines Mitglieds von Nordkreuz – "linke Persönlichkeiten" zu finden und sie "im Konfliktfall zu liquidieren". Mehr als sechs Jahre nach dem Sicherheitsvorfall wandern die Daten noch immer umher, zuletzt in verschwörungsideologischen Telegram-Gruppen.

Derartige Sicherheitsvorfälle mit dem Potenzial körperlicher Schäden und Todesdrohungen sind eine Seltenheit, doch jeder Sicherheitsvorfall brigt unnötige Risiken. Ob sich deine E-Mail-Adresse in bekannten und bei den Anbietern katalogisierten Leaks befindet, kannst du das mit [haveibeenpwned](https://haveibeenpwned.com) oder dem [Leak-Checker des HPI](https://sec.hpi.de/ilc/search?lang=de) selbst prüfen.

## Überwachung – nichts zu verbergen?

Die Begehrlichkeiten des Staates machen vor dem Internet nicht Halt. Im Gegenteil: Die Digitalisierung eröffnet Überwachungsmöglichkeiten, die früher undenkbar waren. "Vorratsdatenspeicherung" und digitale Rasterfahndung, der "Staatstrojaner", Identifikationspflichten, die geplante Einführung einer Bürger-ID und Datenschutzdesaster wie das elektronische Anwaltspostfach sind nur einige Beispiele für gefährliche Instrumente, denen oft nachgesagt wird, "nicht in die falschen Hände geraten" zu dürfen. Tatsächlich stellt schon die Einsatzmöglichkeit dieser Instrumente ein Risiko dar. Die oft geforderte Absenkung der Hürden, unter denen Behörden auf die erhobenen Daten zugreifen dürfen, tut ihr Übriges.

Die staatliche Überwachung der analogen und digitalen Welt wird oft mit der "Sicherheit" der überwachten Bürgerinnen und Bürger begründet, ohne die Gegenargumente zu betrachten. Dabei ist eine reale Konsequenz, dass Menschen schon bei der Möglichkeit, überwacht zu werden, ihr Verhalten ändern – Überwachung formt Untergebene. Reale Probleme löst Überwachung offenbar kaum – anders ist die ständige Forderung nach neuen Überwachungsbefugnissen nicht zu erklären.

## Datenhandel und Werbung

Das [Privacy-Handbuch](https://privacy-handbuch.de/handbuch_11.htm) und [selbstdatenschutz.info](https://web.archive.org/web/20210618051140/https://www.selbstdatenschutz.info/datenkraken/) bieten einen guten Überblick über Akteure, Methoden und Geschäftsmodelle des digitalen Datenhandels und der Nutzerverfolgung.

## Literaturtipps

* [Cory Doctorow: Daten – das neue Öl oder Potenzial für eine Ölkatastrophe?](https://dys2p.com/de/2021-03-new-oil.html)
* [J. Onaolapo, E. Mariconti, G. Stringhini 2016: What Happens After You Are Pwnd: Understanding The Use Of Leaked Webmail Credentials In The Wild](https://www.researchgate.net/publication/310116406_What_Happens_After_You_Are_Pwnd_Understanding_The_Use_Of_Leaked_Webmail_Credentials_In_The_Wild)

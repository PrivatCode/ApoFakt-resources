# Version 5.3.11.0 (öff. voraussichtlich Ende November)
- [x] #1610 - In der Rezeptliste werden stornierte Rezepte mitangezeigt (es wurde ein neuer Filter: 'Nur stornierte Rezepte anzeigen' eingerichtet).
- [x] #1623 - SOK ausfiltern: die SOK-PZN werden ausgefiltert.
- [x] #1670 - Es wurden unter Informationen Neuerungen deaktiviert und jetzt sind sie über die Webseite verfügbar.
- [x] #1677 - Zyto-Schnittstelle PKV Stückelung - bessere Auswahl der Packungsgrößen. Es werden die bessere Kombinationen von Packungen bei der PKV-Stückelung vorgeschlagen.
- [x] #1724 - Neues Rezept - Kontrolle Artikel vor dem Drucken: neue Spalte. Es wurde eine neue Spalte Artikelinfo mit den Informationen aus ABDA-Artikelstamm eingerichtet.
- [x] #1734 - Zyto-Schnittstelle - fehlende ABDA bei den Komponenten.
- [x] #1739 - Auswertungen - Diagramm Fehler. Die Reihenfolge der Monate hat nicht gestimmt. Der Fehler wurde korrigiert.

# Version 5.3.10.1 (x)
- [x] #1733 - 
Neuer Parameter bei Zytoschnittstelle – Optionen: „Keine PKV-Stückelung bei Trägerlösung“
Über diese Option wird die PKV-Stückelung bei den Trägerlösungen ausgeschlossen, d.h. es wird im Verhältnis 1:1 das abgerechnet, 
was bei der Produktion jeweiliger Verordnung hergestellt wurde. Wird diese Option nicht eingesetzt, 
werden die Packungen von Trägerlösungen genauso wie die Wirkstoffe betrachtet, d.h.es wird laut dem obigen Parameter: 
geringster Preis/geringster Verwurf die beste Kombination von Packungen vorgeschlagen.

# Version 5.3.10.0 (12.10.2023)
- [x] #1591 - In dem eigenem Patientenstamm kann die Option Einwilligung Datenweiterleitung aktiviert werden.
- [x] #1638 - In den Musterrezepturen wurde eine neue Option 'SOK für Par. 11' eingerichtet. Beim Taxieren nach Par. 11 (IK=30) wird das neue Feld 'SOK für Par.11'und beim Taxieren nach Par. 129a(IK=26) dasalte Feld 'SOK' verwendet.
- [x] #1642
- [x] #1665
- [x] #1712 - Für die PZN 06460518 (=Arbeitspreis) soll das Preiskennzeichen automatisch in der Taxierung gesetzt werden: bei öff. Apotheken (APOTYP=30) soll das PreisKZ=74 und und bei KH-Apotheken (APOTYP=26) das Preiskz=76 automatisch gesetzt werden.
- [x] #1672 - In den Kassengruppen werden jetzt standardmäßig aktive Formeln angezeigt.
- [x] #1702 - Im Ext. Artikelstamm wurde die Fenstergröße von Kennzeichenhistorie optimiert.
- [x] #1714 - Export CSV - beim Speichern der Exportdatei wird jetzt standarmäßig eine neue Arbeitsmappe vorgeschlagen. Filename/Path ist selektierbar.
- [x] #1717 - Patientenstamm - Zuzahlungsbefreiung für alle Patienten - es wurde eine Abfrage eingebaut.
- [x] #1735 - ConnectX für Cato Schnittstelle- fehlende PatientenID (VersichertenNr.) Patientenzuordnung anhand Name und Geburtsdatum, falls PatientenID nicht vorhanden.

# Version 5.3.9.1 (06.09.2023)
- [x] #1656
- [x] #1671 - Externer Artikelstamm - Modul Interaktionen wurde deaktiviert.
- [x] #1657 - Zyto-Schnittstelle (CATO)- es wurde ein neuer Filter: ArztID eingebaut.
- [x] #1674 - eRezept - Fehlermeldung nach Freigabe und Signieren eines eRezeptes wegen fehlendem Rezeptkommentar in Apofakt beim Taxieren des eRezeptes wurde korrigiert.
- [x] #1675 - e-Rezept - Freigabe/Signieren von PKV eRezepten in ApoFAKT wurde deaktiviert.
- [x] #1682 - Sortierung in Grid - es wurde neue Funktion "Sortierung Zurücksetzen" (mit dem rechten Mausklick auf die erste Spalte/erste Zeile) eingerichtet.
- [x] #1713 - Es kann bei der Wirkstoffanpassung in der Zyto-Schnittstelle nach Kassengruppennamen gefiltert werden.

# Version 5.3.9 (21.08.2023)
- [x] #1634 - Neues Rezept - Einwilligung Datenweiterleitung: Patientendaten aus dem elektronischen Rezept werden nicht mehr überschrieben.
- [x] #1635 - Zuzahlungsbefreiung wird aus der CATO XML-Datei über die ZYTO-SST mitübernommen.
- [x] #1636 - Übernahme von Patientendaten aus CATO xml Datei, wenn Pat.ID nicht vorhanden.
Für solche Fälle wird im ApoFAKT eine interne ApoFAKT-ID generiert.
Die ApoFAKT-ID startet ab den Wert 10000000, (kann auch Kundenindividuell angepasst werden). 
Die PatientenID wird automatisch nach dem Import der Herstellungsdatei in ApoFAKT generiert.
- [x] #552 - Taxierung - Musterrezeptur - Hauslisteartikel wurden mit einer Farbe hervorgehoben.
- [x] #1507 
- [x] #1549 
- [x] #1508 - Zyto-Schnittstelle - es wurden Korrekturen bei der PKV Stückelung (YERVOY, Docetaxel) vorgenommen.
- [x] #955 - eRezept - Zytostatikum: Dosierungshinweis aus der eVeordnung wird dargestellt.
- [x] #1531 - TaxChecker - Vertrag öffnen: Multiformel werden automatisch erstellt.
- [x] #1538 - FAM über Herstellungschnittstelle: Faktorberechnung wurde angepasst (5 Datensätze (Verordnungen) = Faktor 5).
- [x] #1551 
- [x] #1555 
- [x] #1606 - Fertigarzneimittel über CATO Zyto-Schnittstelle. 
Faktorfehler beim Taxieren von Fertigarzneimitteln mit mehreren Wirkstoffen (z.B. PHESGO) - 1800mg => 1. Pack.
Ab jetzt wird bei solchen Fertigarzneimitteln (mit mehr als 1 Wirkstoff) Faktor 1 gesetzt.
- [x] #1560 - Zyto-Schnittstelle - Tabelle mit den Komponenten: Spaltennamen ""Pack. Menge"" wurde in ""Pack. Menge laut ABDA"" umbenannt.
- [x] #1577 - eRezept: automatische Auswahl der ApoNr/IK, keine Korrektur möglich.
- [x] #1584 - eRezept: Apothekenstamm: Darstellung der Apotheken, die für das eRezept ausgeschlossen sind (NES-Ignore Spalte).
- [x] #1590 - eRezept: Verwaltungsmodul für die KIM-Adressen.
- [x] #1593 - eRezept: erst nach Klicken auf ""PZN Hinzuf."" wird die Verordnung hinzugefügt. Dadurch kann man jetzt die Kassengruppe vor der Taxierung anpassen.
- [x] #1594 - ApoCONNECT: @-Rezepte - Export Spalten.
- [x] #1596 - eRezept: neue Tabellen für die Zusatzattributen und Rezeptänderungen wurden eingerichtet.
- [x] #1602 - Optionen - Verbindung - GKV/PKV Rezepte werden nicht übertragen - die Beschreibung der Option wurde optimiert.
- [x] #1614 - eRezept - die Dosierung bei der Freitextverordnung wird dargestellt.
- [x] #1616 - Volltext-Suche in folgenden Modulen:
- Artikelstamm (Eigene Artikel - Name)
- Arztstamm (Name, IK, LANR, Strasse, PLZ, Ort, RefNr., RefNr.2, Indikationsnr., ExtArztID, ExtArztID2)
- Kassenstamm (Kassennummer, IK, Kassenname, PLZ, Ort)
- Kassengruppen (ID, Kassengruppenname, Suchbegriff)
- externe Patientenstammdaten (ID, Name, Versichertennummer, Vorname, PatientenID)
- Patientenstammdaten (Name, Vorname, Versichertennummer,Strasse, Ort, Land)
- [x] #1618 
- [x] #1619 
- [x] #1620 - eRezept - Zusatzattribute: 7 (Wirkstoffverordnung), 10 (einzeln importierte Fertigarzneimittel (§ 73 Abs. 3 AMG)) sowie 15 (Zuzahlungsbefreiung) wurden implementiert.
- [x] #1607 - eRezept: Zusatzattribut und Rezeptänderungen wurden in der Rezeptliste dargestellt.
- [x] #1621 - eRezept: UI Komponente für Rezeptanforderung in der Taxierungsmaske, Auswahl der KIM-Adresse für Empfänger.
- [x] #1625 - eRezept PKV - bei dem Taxierungsvorgang wird der Rezepttyp automatisch auf PKV umgestellt.
- [x] #1486 - eRezept - Inhalt der technischen Tabellen (Queue Tabellen für Rezeptanforderung und Rezeptabruf) wurde dargestellt

# Version 5.3.8.4 (24.07.2023)
- [x] #1608 - Warnung "fehlender Wirkstoff" in der Herstellungsschnittstelle wurde rausgenommen.
- [x] #1609 - Rezeptliste: Sortierung über die erste Spalte (Typ) wurde aktiviert.
- [x] #1615 - Taxierung von Hilfsmitteln: Fehlermeldung in der Rezeptliste: "'xxxxxxxxxx' is not a valid integer value" wurde korrigiert

# Version 5.3.8.3 (14.07.2023)
- [x] #1589 - Rezeptliste - Leistungsverbesserung der SQL-Abfrage in Bezug auf die Anzeige von Informationen über Kassenabsetzungen

# Version 5.3.8.2 (10.07.2023)
- [x] #1561 - Externe Patientendaten - Einwilligung der Datenweiterleitung Auswahl über ComboBox, farbige Darstellung.
- [x] #1566 - ZYTO-Schnittstelle - Suchfunktion nach Vornamen und Geburtsdatum.
- [x] #1576 - Tabelle HRS_MESSAGE - neuer Index auf ERezeptID wurde hinzugefügt
- [x] #1581 - Tabelle ERP_VERORDNUNG - neue Spalte ERP_TIMESTAMP wurde eingerichtet

# Version 5.3.8.1 (28.06.2023)
- [x] #1542 - Beim Kopieren/Korrigieren von AMG-Rezepten wurde die Option "Formel verwenden" automatisch deaktiviert.
Dadurch wurde ein anderer Preis (eventuell auch MwSt.) berechnet.
Betroffen sind die ABDA-Artikel ohne Taxierungsformel auf Artikelebene.

# Version 5.3.8.0 (15.06.2023)
- [x] #1232 - Externer Artikelstamm: die Felder im Reiter Allgemein wurden so erweitert, dass sich die neuen langen Artikeltypen mit den Artikelinformationen nicht mehr überlappern.
- [x] #1245 - Modul Neues Rezept und @Rezept: die Icons bei den PKV Rezepten wurden angepasst (blaue Rezepte).
- [x] #1411 - Taxierungformeln wurden um die neue Variable IMPFRAB (Impfstoffrabatt) erweitert.
- [x] #1420 - Das Modul ABDA Update Freischaltung wurde aus dem Programm entfernt.
- [x] #1432 - Modul Tax-Checker: der geöffnete Dateiname (Vertragsdatei) wird in der Kopfzeile angezeigt.
- [x] #1433 - Modul Tax-Checker: Zeilenmarkierungen (Farben) werden jetzt nur in dem Feld Beschreibung dargestellt. Die Formel-Prüfroutine wurde optimiert und nur nach Bedarf ausgeführt.
- [x] #1448 - Standardansichten/Benutzeransichten: PKV - Auswahlbox In allen Ansichten werden standardmäßig nur die GKV Rezepte dargestellt. Mit der Checkbox kann man auf die PKV Rezepte umswitchen.
- [x] #1449 - Rezeptkopiervorgang:
Bei einem Kopiervorgang wurde zur Zeit die Patient-Gebührenbefreiung im Patientenstamm geprüft.
Hat sich der Status in der Zwischenzeit geändert, wurde ein Hinweis dargestellt.
Dieser Vorgang hat aber wenig Sinn bei den Patienten aus dem Ext.-Artikelstamm. Aus diesem Grund wurde diese Prüfung deaktiviert.
- [x] #1456 - Zyto-Schnittstelle: Produkte mit der Einheit "μg" wurden zur Zeit nicht richtig umgerechnet. Das wurde jetzt angepasst, die Promille sollen ab jetzt korrekt berechnet werden.
- [x] #1470 - ZYTO-Schnittstelle/Berechtigungen Für das Modul ZYTO-Schnittstelle können jetzt pro Benutzer die Berechtigungen gesetzt werden (Open/Config/Delete/Split)
- [x] #1471 - Neues Rezept: jetzt kann man pro Rezept beim Verlauf Kommentare hinterlegen.
- [x] #1473 - TaxChecker: die SOK werden jetzt in der Liste nicht mehr als SOK (PZN), sondern als SOK-Variablen dargestellt.
- [x] #1474 - Zyto-Schnittstelle: Sortieren der Spalten wurde optimiert.
- [x] #1477 - Zyto-Schnittstellle: neue Spalte ZUBEREITUNGID (interne ApoFAKT-ID) wurde als ApoFAKTID Spalte in der Gridd eingebaut.
- [x] #1480 - TaxChecker: neues Feld APOTYP wurde eingebaut.
- [x] #1481 - TaxChecker: Fehler bei Zeilenmarkierung wurde korrigiert.
- [x] #1487 - Musterrezepturen: Spalte 'Verwurf' wurde in 'zzgl. Verwurf' umbenannt. Wird der Verwurf auf 'Ja' gesetzt, wird er beim Taxieren in der Rezeptur automatisch berechnet.
- [x] #1488 - Artikelstamm: Kopierfunktion wurde eingebaut. Man kann jetzt z.B. die Arbeitspreise schneller eingeben.
- [x] #1489 - Artikelstammdaten: Taxierungsformeln für eigene Artikel. Man kann für die eigenen Artikel (z.B Arbeitspreise) Taxierungsformeln hinterlegen. Diese Formeln werden beim Taxieren von Rezepturen mitberücksichtigt.
- [x] #1502 - Neues Rezept: ein Rundungsfehler bei der Formelberechnung wurde behoben.
- [x] #1506 - Zyto-Schnittstelle: bei dem Taxiervorgang wird die verwendete Musterrezeptur-ID anzeigt. Dadurch kann man besser sehen, welche Musterrezeptur automatisch ausgewählt wurde.
- [x] #1509 - Taxieren von Sprechstundenbedarf - Zuzahlung darf nicht berechnet werden. 
- [x] #1510 - Tax-Checker: Optimierung mit Variablen SOKVOLL SOKERM
- [x] #1515 - Zyto-Schnittstelle: Lila Markierung (gesperrter Datensatz) wird jetzt nur dann angezeigt, wenn Verwurfsabrechnung in der Konfiguration aktiviert ist.
- [x] #1516 - eRezept: Beim Taxieren von eRezept wird die KassenIK aus der eVerordnung ausgelesen und dem Kostenträger zugeordnet. Ist der Kostenträger zu einer Kassengruppe zugeordnet, wird die Gruppe automatich ausgewählt. Ist der Kostenträger zu keiner Kassengruppe zugeordnet, wird die Standard-Kassengruppe ausgewählt. 
- [x] #1518 - Externe Patienten: Übertragung von Patientendaten, es wurde eine Checkbox Patientendaten ans RZ nicht übertragen eingerichtet.
- [x] #1519 - Zyto-Schnittstelle: es wurde die Substitution bei den Fertigarzneimitteln aus der Schnittstelle (günstigste FAMs) eingerichtet.
- [x] #1520 - Ext.-Artikelstamm: es wurde bei der Berechnungsweise der Stoffmenge eine leere Zeile hinzugefügt, mithilfe deren die gesetzte Berechnungsweise rückgängig gemacht werden kann.
- [x] #1524 - Externe Patienten/Neues Rezept: bei den Patienten, die wegen Datenschutz nicht zugestimmt haben, ihre Patientendaten ans RZ zu übertragen, kommt ein Pop-up-Fenster.
- [x] #1530 - Neues Rezept: es wurden neue Taxierungsvariablen (SOK-Variablen), die bei den Multiformeln angewendet werden, eingebaut.
MWST_SOK - Mehrwertsteuersatz, der im SOK übermittelt wird, prozentual
SOKVOLL - ergibt 1, wenn SOK des Artikels mit vollem MWST, sonst 0
SOKERM - ergibt 1, wenn SOK des Artikels mit ermäßigtem MWST, sonst 0
SOKMS - ergibt 1, wenn SOK des Artikels mit MWST (voll oder erm.), sonst 0
SOKOHNE - ergibt1, wenn SOK des Artikels mit steuerfrei ist, sonst 0

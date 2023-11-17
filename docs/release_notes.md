test

#Version 5.3.11.0 (x)

#1623 
<br>
ERezept - SOK ausfiltern: die SOK-PZN werden ausgefiltert.
<br>

#1677
<br>
Zyto-Schnittstelle PKV Stückelung - bessere Auswahl der Packungsgrößen
Es werden die bessere Kombinationen von Packungen bei der PKV-Stückelung vorgeschlagen.
<br>

#1724 
Neues Rezept  - Kontrolle Artikel vor dem Drucken: neue Spalte
<br>
Es wurde eine neue Spalte Artikelinfo mit den Informationen aus ABDA-Artikelstamm eingerichtet.
<br>

#1734
<br>
Zyto-Schnittstelle - fehlende ABDA bei den Komponenten
<br>

#1739
<br> 
Auswertungen - Diagramm Fehler
Die Reihenfolge der Monate hat nicht gestimmt. Der Fehler wurde korrigiert.
<br>


#Version 5.3.10.1 (x)
#1733
<br>
Neuer Parameter bei Zytoschnittstelle – Optionen: „Keine PKV-Stückelung bei Trägerlösung“
Über diese Option wird die PKV-Stückelung bei den Trägerlösungen ausgeschlossen, d.h. es wird im Verhältnis 1:1 das abgerechnet, 
was bei der Produktion jeweiliger Verordnung hergestellt wurde. Wird diese Option nicht eingesetzt, 
werden die Packungen von Trägerlösungen genauso wie die Wirkstoffe betrachtet, d.h.es wird laut dem obigen Parameter: 
geringster Preis/geringster Verwurf die beste Kombination von Packungen vorgeschlagen.
<br>

#Version 5.3.10.0 (12.10.2023)

#1591 
<br>
In dem eigenem Patientenstamm kann die Option Einwilligung Datenweiterleitung aktiviert werden.
<br>

#1638
<br>
In den Musterrezepturen wurde eine neue Option 'SOK für Par. 11'  eingerichtet. 
Beim Taxieren nach Par. 11 (IK=30) wird das neue Feld 'SOK für Par.11'und beim Taxieren nach Par. 129a(IK=26) dasalte Feld 'SOK' verwendet. 
<br>

#1642
#1665
#1712
<br>
Für die PZN 06460518 (=Arbeitspreis) soll das Preiskennzeichen automatisch in der Taxierung gesetzt werden:
bei öff. Apotheken (APOTYP=30) soll das PreisKZ=74 und und bei KH-Apotheken (APOTYP=26) das Preiskz=76 automatisch gesetzt werden.
<br>

#1672
<br>
In den Kassengruppen werden jetzt standardmäßig aktive Formeln angezeigt.
<br>

#1702
<br>
Im Ext. Artikelstamm wurde die Fenstergröße von Kennzeichenhistorie optimiert.
<br>

#1714
<br>
Export CSV - beim Speichern der Exportdatei wird jetzt standarmäßig eine neue Arbeitsmappe vorgeschlagen. Filename/Path ist selektierbar.
<br>

#1717
<br>
Patientenstamm - Zuzahlungsbefreiung für alle Patienten - es wurde eine Abfrage eingebaut.
<br>

#1735
<br>
ConnectX für Cato Schnittstelle- fehlende PatientenID (VersichertenNr.) Patientenzuordnung anhand Name und Geburtsdatum, falls PatientenID nicht vorhanden.
<br>

#Version 5.3.9.1 (06.09.2023)

#1656
#1671
<br>
Externer Artikelstamm - Modul Interaktionen wurde deaktiviert.
<br><br>

#1657
<br>
Zyto-Schnittstelle (CATO)- es wurde ein neuer Filter: ArztID eingebaut.
<br><br>


#1674
<br>
eRezept - Fehlermeldung nach Freigabe und Signieren eines eRezeptes wegen 
fehlendem Rezeptkommentar in Apofakt beim Taxieren des eRezeptes wurde korrigiert.
<br><br>

#1675
<br>
e-Rezept - Freigabe/Signieren von PKV eRezepten in ApoFAKT wurde deaktiviert.
<br><br>

#1682
<br>
Sortierung in Grid - es wurde neue Funktion "Sortierung Zurücksetzen" (mit dem rechten Mausklick auf die erste Spalte/erste Zeile) eingerichtet.
<br><br>

#1713
<br>
Es kann bei der Wirkstoffanpassung in der Zyto-Schnittstelle nach Kassengruppennamen gefiltert werden.
<br>

# Version 5.3.9 (21.08.2023)

#1634 
<br>
Neues Rezept - Einwilligung Datenweiterleitung: Patientendaten aus dem elektronischen Rezept werden nicht mehr überschrieben
<br><br>

#1635 
<br>
Zuzahlungsbefreiung wird aus der CATO XML-Datei über die ZYTO-SST mitübernommen
<br><br>

#1636 
<br>
Übernahme von Patientendaten aus CATO xml Datei, wenn Pat.ID nicht vorhanden
Für solche Fälle wird im ApoFAKT eine interne ApoFAKT-ID generiert.
Die ApoFAKT-ID startet ab den Wert 10000000, (kann auch Kundenindividuell angepasst werden). 
Die PatientenID wird automatisch nach dem Import der Herstellungsdatei in ApoFAKT generiert.
<br><br>

#552 
<br>
Taxierung - Musterrezeptur - Hauslisteartikel wurden mit einer Farbe hervorgehoben
<br><br>

#1507 <br>
#1549 <br>
#1508 <br>
Zyto-Schnittstelle - es wurden Korrekturen bei der PKV Stückelung (YERVOY, Docetaxel) vorgenommen
<br><br>

#955 
<br>
eRezept - Zytostatikum: Dosierungshinweis aus der eVeordnung wird dargestellt
<br><br>

#1531 
<br>
TaxChecker - Vertrag öffnen: Multiformel werden automatisch erstellt
<br><br>

#1538 
<br>
FAM über Herstellungschnittstelle: 
Faktorberechnung wurde angepasst (5 Datensätze (Verordnungen) = Faktor 5)
<br><br>

#1551 <br>
#1555 <br>
#1606 <br>
Fertigarzneimittel über CATO Zyto-Schnittstelle. 
Faktorfehler beim Taxieren von Fertigarzneimitteln mit mehreren Wirkstoffen (z.B. PHESGO) - 1800mg => 1. Pack.
Ab jetzt wird bei solchen Fertigarzneimitteln (mit mehr als 1 Wirkstoff) Faktor 1 gesetzt.
<br><br>

#1560 
<br>
Zyto-Schnittstelle - Tabelle mit den Komponenten: Spaltennamen ""Pack. Menge"" wurde in ""Pack. Menge laut ABDA""  umbenannt
<br><br>

#1577 
<br>
eRezept: automatische Auswahl der ApoNr/IK, keine Korrektur möglich.
<br><br>

#1584 
<br>
eRezept: Apothekenstamm: Darstellung der Apotheken, die für das eRezept ausgeschlossen sind (NES-Ignore Spalte)
<br><br>

#1590 
<br>
eRezept: Verwaltungsmodul für die KIM-Adressen
<br><br>

#1593 
<br>
eRezept: erst nach Klicken auf ""PZN Hinzuf."" wird die Verordnung hinzugefügt.
Dadurch kann man jetzt die Kassengruppe vor der Taxierung anpassen.
<br><br>

#1594 
<br>
ApoCONNECT: @-Rezepte - Export Spalten
<br><br>

#1596 
<br>
eRezept: neue Tabellen für die Zusatzattributen und Rezeptänderungen wurden eingerichtet
<br><br>

#1602 
<br>
Optionen - Verbindung - GKV/PKV Rezepte werden nicht übertragen - die Beschreibung der Option wurde optimiert
<br><br>

#1614 
<br>
eRezept - die Dosierung bei der Freitextverordnung wird dargestellt.
<br><br>

#1616 
<br>
Volltext-Suche in folgenden Modulen:
- Artikelstamm (Eigene Artikel - Name)
- Arztstamm (Name, IK, LANR, Strasse, PLZ, Ort, RefNr., RefNr.2, Indikationsnr., ExtArztID, ExtArztID2)
- Kassenstamm (Kassennummer, IK, Kassenname, PLZ, Ort)
- Kassengruppen (ID, Kassengruppenname, Suchbegriff)
- externe Patientenstammdaten (ID, Name, Versichertennummer, Vorname, PatientenID)
- Patientenstammdaten (Name, Vorname, Versichertennummer,Strasse, Ort, Land)
<br><br>

#1618 <br>
#1619 <br>
#1620 <br>
eRezept - Zusatzattribute: 7 (Wirkstoffverordnung), 10 (einzeln importierte Fertigarzneimittel (§ 73 Abs. 3 AMG)) sowie
15 (Zuzahlungsbefreiung) wurden implementiert 
<br><br>

#1607 
<br>
eRezept: Zusatzattribut und Rezeptänderungen wurden in der Rezeptliste dargestellt
<br><br>

#1621 
<br>
eRezept: UI Komponente für Rezeptanforderung in der Taxierungsmaske, Auswahl der KIM-Adresse 
für Empfänger
<br><br>

#1625 
<br>
eRezept PKV - bei dem Taxierungsvorgang wird der Rezepttyp automatisch auf PKV umgestellt
<br><br>

#1486 
<br>
eRezept - Inhalt der technischen Tabellen (Queue Tabellen für Rezeptanforderung und Rezeptabruf) wurde dargestellt
<br><br>



# Version 5.3.8.4 (24.07.2023)

#1608
<br>
Warnung "fehlender Wirkstoff" in der Herstellungsschnittstelle wurde rausgenommen.
<br><br>

#1609
<br>
Rezeptliste: Sortierung über die erste Spalte (Typ) wurde aktiviert.
<br><br>

#1615
<br>
Taxierung von Hilfsmitteln: Fehlermeldung in der Rezeptliste: "'xxxxxxxxxx' is not a valid integer value" wurde korrigiert
<br><br>

# Version 5.3.8.3 (14.07.2023)

#1589
<br>
Rezeptliste - Leistungsverbesserung der SQL-Abfrage in Bezug auf die Anzeige von Informationen über Kassenabsetzungen
<br><br>

# Version 5.3.8.2 (10.07.2023)

#1561
<br>
Externe Patientendaten - Einwilligung der Datenweiterleitung 
Auswahl über ComboBox, farbige Darstellung.
<br><br>

#1566
<br>
ZYTO-Schnittstelle - Suchfunktion nach Vornamen und Geburtsdatum
<br><br>

#1576
<br>
Tabelle HRS_MESSAGE - neuer Index auf ERezeptID wurde hinzugefügt
<br><br>

#1581
<br>
Tabelle ERP_VERORDNUNG - neue Spalte ERP_TIMESTAMP wurde eingerichtet
<br><br>



# Version 5.3.8.1 (28.06.2023)

#1542
<br>
Beim Kopieren/Korrigieren von AMG-Rezepten wurde die Option "Formel verwenden" automatisch deaktiviert.
Dadurch wurde ein anderer Preis (eventuell auch MwSt.) berechnet.
Betroffen sind die ABDA-Artikel ohne Taxierungsformel auf Artikelebene.
<br><br>

# Version 5.3.8.0 (15.06.2023)

#1232
<br>
Externer Artikelstamm: die Felder im Reiter Allgemein wurden so erweitert, 
dass sich die neuen langen Artikeltypen mit den Artikelinformationen nicht mehr überlappern.
<br><br>

#1245
<br>
Modul Neues Rezept und @Rezept: die Icons bei den PKV Rezepten wurden angepasst (blaue Rezepte).
<br><br>

#1411
<br>
Taxierungformeln wurden um die neue Variable IMPFRAB (Impfstoffrabatt) erweitert.
<br><br>

#1420
<br>
Das Modul ABDA Update Freischaltung wurde aus dem Programm entfernt.
<br><br>

#1432
<br>
Modul Tax-Checker: der geöffnete Dateiname (Vertragsdatei) wird in der Kopfzeile angezeigt.
<br><br>

#1433
<br>
Modul Tax-Checker: Zeilenmarkierungen (Farben) werden jetzt nur in dem Feld Beschreibung dargestellt.
Die Formel-Prüfroutine wurde optimiert und nur nach Bedarf ausgeführt.
<br><br>

#1448
<br>
Standardansichten/Benutzeransichten: PKV - Auswahlbox
In allen Ansichten werden standardmäßig nur die GKV Rezepte dargestellt.
Mit der Checkbox kann man auf die PKV Rezepte umswitchen.
<br><br>

#1449
<br>
Rezeptkopiervorgang:
Bei einem Kopiervorgang wurde zur Zeit die Patient-Gebührenbefreiung im Patientenstamm geprüft.
Hat sich der Status in der Zwischenzeit geändert, wurde ein Hinweis dargestellt.
Dieser Vorgang hat aber wenig Sinn bei den Patienten aus dem Ext.-Artikelstamm. Aus diesem Grund wurde diese Prüfung deaktiviert.
<br><br>

#1456
<br>
Zyto-Schnittstelle: Produkte mit der Einheit "μg" wurden zur Zeit nicht richtig umgerechnet.
Das wurde jetzt angepasst, die Promille sollen ab jetzt korrekt berechnet werden.
<br><br>

#1470
<br>
ZYTO-Schnittstelle/Berechtigungen
Für das Modul ZYTO-Schnittstelle können jetzt pro Benutzer die Berechtigungen gesetzt werden (Open/Config/Delete/Split)
<br><br>

#1471
<br>
Neues Rezept: jetzt kann man pro Rezept beim Verlauf Kommentare hinterlegen.
<br><br>

#1473
<br>
TaxChecker: die SOK werden jetzt in der Liste nicht mehr als SOK (PZN), sondern als SOK-Variablen dargestellt.
<br><br>

#1474
<br>
Zyto-Schnittstelle: Sortieren der Spalten wurde optimiert.
<br><br>

#1477
<br>
Zyto-Schnittstellle: neue Spalte ZUBEREITUNGID (interne ApoFAKT-ID) wurde als ApoFAKTID Spalte in der Gridd eingebaut.
<br><br>

#1480
<br>
TaxChecker: neues Feld APOTYP wurde eingebaut.
<br><br>

#1481
<br>
TaxChecker: Fehler bei Zeilenmarkierung wurde korrigiert.
<br><br>

#1487
<br>
Musterrezepturen: Spalte 'Verwurf' wurde in 'zzgl. Verwurf' umbenannt. Wird der Verwurf auf 'Ja' gesetzt,
wird er beim Taxieren in der Rezeptur automatisch berechnet.
<br><br>

#1488
<br>
Artikelstamm: Kopierfunktion wurde eingebaut. 
Man kann jetzt z.B. die Arbeitspreise schneller eingeben.
<br><br>

#1489
<br>
Artikelstammdaten: Taxierungsformeln für eigene Artikel.
Man kann für die eigenen Artikel (z.B Arbeitspreise) Taxierungsformeln hinterlegen.
Diese Formeln werden beim Taxieren von Rezepturen mitberücksichtigt.
<br><br>

#1502
<br>
Neues Rezept: ein Rundungsfehler bei der Formelberechnung wurde behoben.
<br><br>

#1506
<br>
Zyto-Schnittstelle: bei dem Taxiervorgang wird die verwendete Musterrezeptur-ID anzeigt.
Dadurch kann man besser sehen, welche Musterrezeptur automatisch ausgewählt wurde.
<br><br>

#1509
<br>
Taxieren von Sprechstundenbedarf - Zuzahlung darf nicht berechnet werden. 
<br><br>

#1510
<br>
Tax-Checker: Optimierung mit Variablen SOKVOLL SOKERM
<br><br>

#1515
<br>
Zyto-Schnittstelle: Lila Markierung (gesperrter Datensatz) wird jetzt nur dann angezeigt, wenn Verwurfsabrechnung in der Konfiguration aktiviert ist.
<br><br>

#1516
<br>
eRezept: Beim Taxieren von eRezept wird die KassenIK aus der eVerordnung ausgelesen und dem Kostenträger zugeordnet.
Ist der Kostenträger zu einer Kassengruppe zugeordnet, wird die Gruppe automatich ausgewählt.
Ist der Kostenträger zu keiner Kassengruppe zugeordnet, wird die Standard-Kassengruppe ausgewählt. 
<br><br>

#1518
<br>
Externe Patienten: Übertragung von Patientendaten, es wurde eine Checkbox Patientendaten ans RZ nicht übertragen eingerichtet.
<br><br>

#1519
<br>
Zyto-Schnittstelle: es wurde die Substitution bei den Fertigarzneimitteln aus der Schnittstelle (günstigste FAMs) eingerichtet.
<br><br>

#1520
<br>
Ext.-Artikelstamm: es wurde bei der Berechnungsweise der Stoffmenge eine leere Zeile hinzugefügt, 
mithilfe deren die gesetzte Berechnungsweise rückgängig gemacht werden kann.
<br><br>

#1524 
<br>
Externe Patienten/Neues Rezept: bei den Patienten, die wegen Datenschutz nicht zugestimmt haben, ihre Patientendaten ans RZ zu übertragen,
kommt ein Pop-up-Fenster.
<br><br>

#1530
<br>
Neues Rezept: es wurden neue Taxierungsvariablen (SOK-Variablen), die bei den Multiformeln angewendet werden, eingebaut.
MWST_SOK - Mehrwertsteuersatz, der im SOK übermittelt wird, prozentual
SOKVOLL - ergibt 1, wenn SOK des Artikels mit vollem MWST, sonst 0
SOKERM - ergibt 1, wenn SOK des Artikels mit ermäßigtem MWST, sonst 0
SOKMS - ergibt 1, wenn SOK des Artikels mit MWST (voll oder erm.), sonst 0
SOKOHNE - ergibt1, wenn SOK des Artikels mit steuerfrei ist, sonst 0
<br><br>
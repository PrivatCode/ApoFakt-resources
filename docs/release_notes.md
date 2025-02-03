# Version 5.4.3.1 (Pilotierung, öff. am 31.01.2025) 
- [x] __#2182__ - Neues Rezept: Chargennr./Verfallsdaten nach Zuordnen eines eRezeptID wieder mitangezeigt.
- [x] __#2201__ - Zyto-Schnittstelle: Chargenübermittlung - Fehler bei dem Parameter 'Verwurf automatisch berechnen' korrigiert.
- [x] __#2202__ - eVerordnungen: Arztübernahme beim Taxieren eines eRezeptes (ASV-Rezept).
- [x] __#2203__ - Arztstammdaten: ASV-eRezept: Umbenennung der Felder: ASV-Teamnummer und ASV-Fachgruppennr.
- [x] __#2207__ - Zyto-Schnittstelle: Fehler bei der Berechnung des Faktors von Menge "pcs of package" bei FAMs korrigiert.

# Version 5.4.3.0 (Pilotierung, öff. am 28.01.2025) 
- [x] __#2068__ - Kassengruppen: Taxformeln in Kassengruppen einlesbar.
- [x] __#2080__ - Refactoring zu #2061 (eVerordnungen: Substitutionsliste bei der Taxierung von eRezept (FAM - PZN) mitberücksichtigt).
- [x] __#2081__ - Refactoring zu #2075 (eVeordnungen: Korrektur beim Setzen des AutIdem Kreuzes und HilfsmittelKZNs beim Taxieren).
- [x] __#2117__ - Neues Rezept: Hinweis auf eine Zuzahlungsermäßigung im Rezept eingebaut.
- [x] __#2121__ - Privatabrechnung: Korrektur bei der Anzeige von Rechnungsnummern.
- [x] __#2125__ - Neues Rezept: Betrag der 'Zuzahlung' pro FAM mitangezeigt.
- [x] __#2133__ - eVerordnungen: Warnung bei der Apotkenennummeränderung beim Taxieren des eRezeptes eingebaut.
- [x] __#2134__ - Taxierung: Organisationseinheiten eingerichtet.
- [x] __#2135__ - eVerordnungen - Direktzuweisung: Änderung der Apotheken-Nummer ermöglicht.
- [x] __#2155__ - Neues Rezept: Organisationseinheiten - Auswahlbox eingerichtet.
- [x] __#2159__ - eVerordnungen - Rezeptänderungen: Combobox bei der Rücksprache eingebaut.
- [x] __#2163__ - ApoCONNECT - @-Rezept: eine neue Spalte 'Apothekennummer'in Excel/CSV-Datei eingebaut.
- [x] __#2165__ - eVerordnungen: Korrektur bei den doppelten eRezeptIDs vorgenommen.
- [x] __#2167__ - eVerordnungen - Rezeptänderung: Kommentare bei dem eRezept nicht mehr automatisch als Rezeptänderung betrachtet.

# Version 5.4.2.3 (öff. am 19.12.2024) 
- [x] __#2118__ - eVerordnungen: Fehler beim Setzen des Zusatzattributs in Bezug auf die Gebührenbefreiung im eRezept korrigiert.

# Version 5.4.2.2 (öff. am 25.11.2024 ) 
- [x] __#2113__ - Zyto-Schnittstelle: Berechnung des Faktors bei den FAMs aus Zyto anhand der Menge (Einheit 'pcs of packages').

# Version 5.4.2.1 (öff. am 22.11.2024) 
- [x] __#2077__ - eRezept: FAM aus Zyto-Schnittstelle - Chargen- und Verfallsdaten aus der Schnittstelle mitübernommen.
- [x] __#2103__ - Neues Rezept: eine neue Spalte 'eRezeptID' im Excel- und CSV-Export eingebaut.

# Version 5.4.2.0 (öff. am 20.11.2024) 
- [x] __#1612__ - @Rezept: Korrektur der Verknüpfungen von doppelten Datensätzen (körperliche Rezepte) vorgenommen.
- [x] __#1862__ - eVerordnungen: Korrektur bei dem Wechseln des Rezepttypes (eRezept/Rezept) vorgenommen.
- [x] __#1873__ - TaxChecker: Zeilen aus einem Vertrag in einen anderen oder anderen bestehenden Vertrag kopierbar gemacht.
- [x] __#1966__ - Rezeptanforderungen: automatische Aktualisierung der Daten.
- [x] __#1990__ - eVerordnungen: neue Schlüssel von Rezeptänderungen zum 01.11.2024 eingerichtet.
- [x] __#1991__ - eVerordnungen: Rezeptänderungen - Rücksprache halten auf true/false setzen.
- [x] __#1994__ - eVerordnungen: Übernahme der PZN-Arzneimittelinformation bei der Dispensierung vor der Taxierung des eRezeptes.
- [x] __#2029__ - Neues Rezept: PZN Reiter - zwei neue Spalten über Rabattverträge: 'PreisKNZ' und 'Rabattvertrag HA3' eingebaut.
- [x] __#2031__ - Neues Rezept: PZN Reiter - Rohertrag als Summe ermittelt.
- [x] __#2043__ - Ext. Artikelstamm: Preishistorie - falsche Anzeige und Berechnung von historischen Daten des Festbetrages korrigiert.
- [x] __#2044__ - Neues Rezept: Hilfsmittelkennzeichen wieder wie früher aufs Rezept (in das aut-idem-Feld) gedruckt.
- [x] __#2046__ - CnX-Dienste: CnX-Preisänderungsdienst - Optimierungen vorgenommen.
- [x] __#2049__ - Zyto-Schnittstelle: Übernahme von Charge und Verfallsdatum für SAP eingerichtet.
- [x] __#2052__ - eVerordnungen: ein neues Zusatzattribut 'Teilmengenabgabe' eingebaut.
- [x] __#2055__ - CnX-Dienste: CnX-Scheduler - Fehler bei der Laufzeit korrigiert.
- [x] __#2056__ - Verordnungsliste: Feld 'Benutzername' in die Verordnungsliste sowie im Excel-Export eingebaut.
- [x] __#2057__ - eVerordnungen/Neues Rezept: Korrektur bei der Reihenfolge von Meldungen (Freigabe/Dispensieren).
- [x] __#2061__ - eVerordnungen: Substitutionsliste bei der Taxierung von eRezept (FAM - PZN) mitberücksichtigt.
- [x] __#2065__ - Neues Rezept: Gültigkeitszeitraum des Rezeptes - Fehlermeldung auf Warnungsmeldung geändert.
- [x] __#2067__ - Ext. Artikelstamm: erweiterte Suche - Fehler bei der Suche nach MG-Menge des Wirkstoffes korrigiert.
- [x] __#2070__ - ApoFAKT: Darstellung von 'Rechenzentrum-IK' bei den Transferkunden.
- [x] __#2073__ - Zyto-Schnittstelle: fehlende eRezeptID nach Zuordnen und Taxieren des eRezeptes eingebaut.
- [x] __#2075__ - eVeordnungen: Korrektur beim Setzen des AutIdem Kreuzes und HilfsmittelKZNs beim Taxieren.
- [x] __#2082__ - Neues Rezept: neuer Reiter 'Charge' und 'Verfallsdatum' eingebaut.
- [x] __#2083__ - Neues Rezept: neue Rezeptur - 'Charge' und 'Verfallsdatum' mit angezeigt.
- [x] __#2091__ - eVerordnungen/Zyto-Schnittstelle: Übernahme des Abgabedatums aus der Dispensierung.
- [x] __#2097__ - Neues Rezept: Format des Verfallsdatums bei den Verwürfen angepasst.

# Version 5.4.1.0 (öff. am 13.08.2024) 
- [x] __#1875__ - Tax-Checker: Korrektur bei der Zeilenauswahl im Tax-Checker.
- [x] __#1976__ - Zyto-Schnittstelle: Betriebsart CYPRO eingerichtet.
- [x] __#1986__ - Neues Rezept: Kommentar hinzufügen - Rechtschreibfehler korrigiert.
- [x] __#1987__ - eVerordnungen/Neues Rezept: Hinzufügen/Bearbeiten der Zusatzattribute vor dem Taxieren eines eRezeptes gesperrt.
- [x] __#1995__ - eVerordnungen - eRezept taxieren: FAM Rechtsschreibfehler korrigiert.
- [x] __#1996__ - Neues Rezept: Rohertrag - EEK von einem eingesetzten Artikel mitberücksichtigt.
- [x] __#1998__ - Ext. Artikelstamm: Rabattverträge Zytostatika - F5 Ersetzen: Suche der Rabattartikel (HA3) nach KassenIK und Region.
- [x] __#1999__ - Apotheken: ein neues Feld 'Region (HA3)' für Rabattartikel (HA3) eingerichtet.
- [x] __#2001__ - Neues Rezept: AMG Rezept - Meldungen in Bezug auf die Rabattartikel (HA3) eingebaut.
- [x] __#2004__ - Neues Rezept: Korrektur der Rohertragsberechnung, wenn Anzahl von Packungen (FAM) >1.
- [x] __#2007__ - Drei neue Felder: Rohertrag-Rez/Rohertrag-PZN/Rohertrag-RRPos in die Benutzeransichten hinzugefügt.
- [x] __#2012__ - Apotheken - Region: Bearbeiten des Regionsnamen gesperrt.

# Version 5.4.0.2 (öff. am 26.06.2024)
- [x] __#1959__ - Neues Rezept: Rohertrag in der Rezeptliste/Details mitangezeigt.
- [x] __#1964__ - Rezeptanforderungen: Optimierungen durchgeführt.
- [x] __#1972__ - eVerordnungen: Dispensierung bei der Auseinzelung - Dar. des ersten Artikels aus der Rezeptur genommen.

# Version 5.4.0.1 (öff. am 11.06.2024)
- [x] __#1967__ - Biosimilars/Referenzartikel: falsche REF-Preise bei historischer Taxierung korrigiert.

# Version 5.4.0.0 (öff. am 06.06.2024)
- [x] __#1869__ - Tax-Checker: Lücken in der Multiformel entfernt.
- [x] __#1895__ - Rezeptanforderungen: erneute Prüfung der Zusatzattribute bei der Rezeptanforderung.
- [x] __#1908__ - Rezeptanforderungen: Arzt/Fallnummner/PatID validiert.
- [x] __#1915__ - Neues Rezept: ein neues Feld 'AMG-Zeitstempel' im Excel-Export eingerichtet.
- [x] __#1928__ - Startpanel: Release Notes + Online Dienste aktualisiert.
- [x] __#1932__ - eVerordungen: fehlendes Feld 'Wirkstoffnummer' hinzufügt.
- [x] __#1938__ - Benutzeransichten: ein neues Feld 'ERezeptID' eingerichtet.
- [x] __#1940__ - ApoFAKT: neuer Reiter 'CnX-Dienste' hinzugefügt.
- [x] __#1941__ - CnX-Dienste: CnX-Scheduler als Windows Service eingerichtet.
- [x] __#1943__ - CnX-Dienste: CnX-Datenabholung eingerichtet.
- [x] __#1943__ - Zyto-Schnittstelle: Datenimport über TCP für die Zyto-Schnittstelle implementiert.
- [x] __#1945__ - CnX: REST API Schnittstelle implementiert.
- [x] __#1946__ - CnX Bibliotheken: Neuer SSHClient in die Datei "CnX.Tools.dll" geschoben.
- [x] __#1947__ - Neues Rezept: Rohertrag für Rezepturen ermittelt.
- [x] __#1948__ - Verordnungsliste: Summe des Rohertrages eingerichtet.
- [x] __#1956__ - Neues Rezept: Zuzahlungsbefreiung prüfen - Rückmeldung aus der Schnittstelle eingebaut.

# Version 5.3.13.1 (öff. am 15.05.2024)
- [x] __#1890__ - ConnectX - Korrektur bei der Übertragung der Rezepte (Datenabholung).
- [x] __#1864__ - eVerodnungen: Zusatzattribute - Korrektur der Fehlermeldung.
- [x] __#1902__ - Neues Rezept: zusätzliche Prüfung der KassenIK auf dem Rezept eingebaut.
- [x] __#1903__ - Neues Rezept: Taxierungsvariablen - IMPFRAB - Korrektur der Berechnung.

# Version 5.3.13.0 (öff. am 09.04.2024)
- [x] __#1864__ - Verordnungsliste: RezeptNr. in der Verordnungsliste eingebaut.
- [x] __#1526__ -TaxChecker - Einrichtung neuer Variablen  SSB, IMPF,HIM.
- [x] __#1761__ - eRezept - eVerordnungen: Ermittteln von Vertragskennzeichen anhand KBV_CS_SFHIR_KBV_STATUSKENNZEICHEN (Zusatzattribut für Ersatzverordnung).
- [x] __#1762__ - Neues Rezept: Korrektur bei der Ersatzverordnung - Zuzahlung darf nicht > 0 sein.
- [x] __#1820__ - eRezept - eVeordnungen: Schlüssel für Rezeptänderungen beim eRezept eingerichtet.
- [x] __#1833__ - eRezept - Zyto-Schnittstelle - eVerordnungen: Übernahme der eRezeptID ins Feld RezeptID.
- [x] __#1834__ - eRezept - eVerordnungen: Korrektur der Fehlermeldung/fehlendes rosa Rezept.
- [x] __#1835__ - eRezept - eVerordnungen: Korrektur der Fehlermeldung: ZYTO - eVerordnungen.
- [x] __#1838__ - eRezept - eVerordnungen: FRX Status hinzugefügt.
- [x] __#1839__ - eRezept - eVerordnungen: Bearbeiten von Zusatzattributen eingerichtet.
- [x] __#1840__ - eRezept - eVerordnungen - Optimierungen bei der Option "Suche nach".
- [x] __#1843__ - eRezept - eVerordnungen: Menüleiste umgebaut.
- [x] __#1849__ - Neues Rezept - Verlauf: Korrektur des Status beim Kopieren eines Rezeptes.
- [x] __#1850__ - eRezept/Neues Rezept - Zusatzattribute bearbeiten : Tooltip eingerichtet.
- [x] __#1854__ - eRezept - eVerordnungen: Zeile mit der laufenden Nummerierung pro PZN bei Zusatzattributen eingerichtet.
- [x] __#1856__ - Externer Artikelstamm: Bearbeiten des Layouts.
- [x] __#1859__ - Neues Rezept: Korrektur des Rundungsfehlers bei der Zuzahlung.
- [x] __#1860__ - Benutzeransichten: Währung bei dem Rezeptur-Faktor entfernt.

# Version 5.3.12.0 (öff. am 15.02.2024)
- [x] __#1811__ - Neues Rezept - Rezeptprüfung 28 Tage: Neue Prüfung, die erkennt, wenn zwischen Verordnungsdatum und Abgabedatum mehr als 28 Tage liegen. Hinweistext:
"Zwischen Verordnungs- und Abgabedatum liegen mehr als 28 Tage. Bitte prüfen Sie, ob das für diese Verordnung gültig ist."
- [x] __#1687__ - Externe Patienten - Spalte 'Einwilligung Datenweiterleitung' – Optimierung der Darstellung.
- [x] __#1749__ - Benutzeransichten: Anzeige der Beschreibung zu einer Benutzeransicht.
- [x] __#1790__ - Neues Rezept – Erweiterung des Excel-Exports um das Feld 'Benutzername'.
- [x] __#1797__ - eRezept - eVerordnungen – Verschieben der Spalte 'Kostenträgertyp'.
- [x] __#1799__ - Neues Rezept - eRezept: Storno von eRezept mit Status IN ABRECHNUNG/ABGERECHNET gesperrt.
- [x] __#1805__ - Neues Rezept - eRezept: Bearbeitung der Zusatzattribute eingerichtet.
- [x] __#1806__ - Neues Rezept - eRezept: Zusatzattribute - Prüfung/Validierung der Zusatzattribute (nach Technische Anlage 7).
- [x] __#1810__ - eRezept - eVerrodnungen: Zuzahlungsbefreiung (Korrektur): Zuzahlungsstatus aus der ärztlichen Verordnung richtig mitübernommen.
- [x] __#1812__ - eRezept - eVerordnungen: Darstellung der FiveRX-Status nach der Übertragung ans Rechenzentrum.
- [x] __#1816__ - eRezept - eVerordnungen: Optimierung beim Laden von Daten.
- [x] __#1819__ - eRezept – eVerordnungen: Korrektur - Faktor aus der ärztlichen Verordnung richtig mitübernommen.
- [x] __#1824__ - eRezept – eVerordnungen: (bugfix) Fehlermeldung beim Versuch ein storniertes Rezept erneut zu taxieren, korrigiert. 
- [x] __#1825__ - Neues Rezept - eRezept: Meldung beim Rezeptstorno angepasst.
- [x] __#1827__ - eRezept – eVerordnungen: Anzeige des Abgabedatums sowie der RezeptNr. auf dem rosa Rezept.
 
# Version 5.3.11.2 (öff. am  22.01.2024)
- [x] __#1795__ - Korrektur der Fehlermeldung bei der Auswahl der Musterrezeptur, Feld zzgl.Verwurf JA + Preisvergleich JA (GKV Rezept)

# Version 5.3.11.1 (öff. am  09.01.2024)
- [x] __#1763__ - Kopierfenster in Rezeptsuche ändern: die Kopierfunktion wird von nun an nur für das angeklickte Feld angeboten, 
nicht für alle Felder.
- [x] __#1775__ - Neues Rezept - Aufnahmenummer wurde auf Fallnummer umbenannt.
- [x] __#1782__ - Deadlock bei dem Programmstart wurde verhindert. 

# Version 5.3.11.0 (öff. am 29.11.2023)
- [x] __#1610__ - In der Rezeptliste werden stornierte Rezepte mitangezeigt (es wurde ein neuer Filter: 'Nur stornierte Rezepte anzeigen' eingerichtet).
- [x] __#1623__ - SOK ausfiltern: die SOK-PZN werden ausgefiltert.
- [x] __#1670__ - Es wurden unter Informationen Neuerungen deaktiviert und jetzt sind sie über die Webseite verfügbar.
- [x] __#1677__ - Zyto-Schnittstelle PKV Stückelung - bessere Auswahl der Packungsgrößen. Es werden bessere Kombinationen von Packungen bei der PKV-Stückelung vorgeschlagen.
- [x] __#1724__ - Neues Rezept - Kontrolle Artikel vor dem Drucken: neue Spalte. Es wurde eine neue Spalte Artikelinfo mit den Informationen aus ABDA-Artikelstamm eingerichtet.
- [x] __#1734__ - Zyto-Schnittstelle - fehlende ABDA bei den Komponenten.
- [x] __#1739__ - Auswertungen - Diagramm Fehler. Der Fehler bei der Reihenfolge der Monate wurde korrigiert.
- [x] __#1743__ - Bei Rezeptstorno kann man einen Stornogrund erfassen. Die Stornogründe werden unter Verlauf mitangezeigt.
- [x] __#1745__ - Tax-Checker Multiformel-Problem wurde gelöst (Syntaxfehler).
- [x] __#1754__ - PKV-Zyto-Schnittstelle-Optionen wurden getrennt sowohl für die Trägerlösungen, als auch für die Wirkstoffe und andere Komponenten umgebaut. 
PKV-Optionen: mg-genaue Übernahme/Aufrunden auf volle Packungseinheit/Stückelung geringster Preis/Stückelung geringster Verwurf
PKV-Optionen bei Trägerlösung: Ohne Aufrunden/Stückelung/Aufrunden auf volle Packungseinheit/Stückelung geringster Preis/Stückelung geringster Verwurf
- [x] __#1755__ - In der Taxierung/Rezeptliste werden die Materialkosten über Excel mitexportiert.
- [x] __#1756__ - Korrektur beim Ausdrucken von Aut-Idem-Kreuz auf dem Rezept. 
Grund: die aut idem Kreuze werden nicht an der richtigen Stelle gedruckt, wenn das SOK für steuerfrei als erste PZN steht. 
Das aut idem Kreuz ist dann immer um 1 Feld zu tief gedruckt und 3 aut idem Kreuz kann man gar nicht drucken, da das 3. dann unten rausfällt. 
Das Kreuz für den ersten Artikel muß an die erste Stelle vor dem Verordnungstext gedruckt werden.
- [x] __#1759__ - Bei den Zyto-Schnittstellen-Optionen wurde ein neuer Parameter: 'Bei PKV nach Hersteller filtern' eingebaut.
- [x] __#1765__ - Der Export in eine JSON-Datei wurde korrigiert.

# Version 5.3.10.1 (öff. am 06.11.2023)
- [x] __#1733__ - 
Neuer Parameter bei Zytoschnittstelle – Optionen: „Keine PKV-Stückelung bei Trägerlösung“
Über diese Option wird die PKV-Stückelung bei den Trägerlösungen ausgeschlossen, d.h. es wird im Verhältnis 1:1 das abgerechnet, 
was bei der Produktion jeweiliger Verordnung hergestellt wurde. Wird diese Option nicht eingesetzt, 
werden die Packungen von Trägerlösungen genauso wie die Wirkstoffe betrachtet, d.h.es wird laut dem obigen Parameter: 
geringster Preis/geringster Verwurf die beste Kombination von Packungen vorgeschlagen.

# Version 5.3.10.0 (öff. am 12.10.2023)
- [x] __#1591__ - In dem eigenem Patientenstamm kann die Option Einwilligung Datenweiterleitung aktiviert werden.
- [x] __#1638__ - In den Musterrezepturen wurde eine neue Option 'SOK für Par. 11' eingerichtet. Beim Taxieren nach Par. 11 (IK=30) wird das neue Feld 'SOK für Par.11', und beim Taxieren nach Par. 129a(IK=26) das alte Feld 'SOK' verwendet.
- [x] __#1642__
- [x] __#1665__
- [x] __#1712__ - Für die PZN 06460518 (=Arbeitspreis) soll das Preiskennzeichen automatisch in der Taxierung gesetzt werden: bei öff. Apotheken (APOTYP=30) soll das PreisKZ=74 und und bei KH-Apotheken (APOTYP=26) das Preiskz=76 automatisch gesetzt werden.
- [x] __#1672__ - In den Kassengruppen werden jetzt standardmäßig aktive Formeln angezeigt.
- [x] __#1702__ - Im Ext. Artikelstamm wurde die Fenstergröße von Kennzeichenhistorie optimiert.
- [x] __#1714__ - Export CSV - beim Speichern der Exportdatei wird jetzt standarmäßig eine neue Arbeitsmappe vorgeschlagen. Filename/Path ist selektierbar.
- [x] __#1717__ - Patientenstamm - Zuzahlungsbefreiung für alle Patienten - es wurde eine Abfrage eingebaut.
- [x] __#1735__ - ConnectX für Cato Schnittstelle- fehlende PatientenID (VersichertenNr.) Patientenzuordnung anhand Name und Geburtsdatum, falls PatientenID nicht vorhanden.

# Version 5.3.9.1 (öff. am 06.09.2023)
- [x] __#1656__
- [x] __#1671__ - Externer Artikelstamm - Modul Interaktionen wurde deaktiviert.
- [x] __#1657__ - Zyto-Schnittstelle (CATO)- es wurde ein neuer Filter: ArztID eingebaut.
- [x] __#1674__ - eRezept - Fehlermeldung nach Freigabe und Signieren eines eRezeptes wegen fehlendem Rezeptkommentar in Apofakt beim Taxieren des eRezeptes wurde korrigiert.
- [x] __#1675__ - e-Rezept - Freigabe/Signieren von PKV eRezepten in ApoFAKT wurde deaktiviert.
- [x] __#1682__ - Sortierung in Grid - es wurde EINE neue Funktion "Sortierung Zurücksetzen" (mit dem rechten Mausklick auf die erste Spalte/erste Zeile) eingerichtet.
- [x] __#1713__ - Es kann bei der Wirkstoffanpassung in der Zyto-Schnittstelle nach Kassengruppennamen gefiltert werden.

# Version 5.3.9 (öff. am 21.08.2023)
- [x] __#1634__ - Neues Rezept - Einwilligung Datenweiterleitung: Patientendaten aus dem elektronischen Rezept werden nicht mehr überschrieben.
- [x] __#1635__ - Zuzahlungsbefreiung wird aus der CATO XML-Datei über die ZYTO-SST mitübernommen.
- [x] __#1636__ - Übernahme von Patientendaten aus CATO xml Datei, wenn Pat.ID nicht vorhanden.
Für solche Fälle wird im ApoFAKT eine interne ApoFAKT-ID generiert.
Die ApoFAKT-ID startet ab den Wert 10000000, (kann auch Kundenindividuell angepasst werden). 
Die PatientenID wird automatisch nach dem Import der Herstellungsdatei in ApoFAKT generiert.
- [x] __#552__ - Taxierung - Musterrezeptur - Hauslisteartikel wurden mit einer Farbe hervorgehoben.
- [x] __#1507__ 
- [x] __#1549__ 
- [x] __#1508__ - Zyto-Schnittstelle - es wurden Korrekturen bei der PKV Stückelung (YERVOY, Docetaxel) vorgenommen.
- [x] __#955__ - eRezept - Zytostatikum: Dosierungshinweis aus der eVeordnung wird dargestellt.
- [x] __#1531__ - TaxChecker - Vertrag öffnen: Multiformel werden automatisch erstellt.
- [x] __#1538__ - FAM über Herstellungschnittstelle: Faktorberechnung wurde angepasst (5 Datensätze (Verordnungen) = Faktor 5).
- [x] __#1551__ 
- [x] __#1555__ 
- [x] __#1606__ - Fertigarzneimittel über CATO Zyto-Schnittstelle. 
Faktorfehler beim Taxieren von Fertigarzneimitteln mit mehreren Wirkstoffen (z.B. PHESGO) - 1800mg => 1. Pack.
Ab jetzt wird bei solchen Fertigarzneimitteln (mit mehr als 1 Wirkstoff) Faktor 1 gesetzt.
- [x] __#1560__ - Zyto-Schnittstelle - Tabelle mit den Komponenten: Spaltennamen ""Pack. Menge"" wurde in ""Pack. Menge laut ABDA"" umbenannt.
- [x] __#1577__ - eRezept: automatische Auswahl der ApoNr/IK, keine Korrektur möglich.
- [x] __#1584__ - eRezept: Apothekenstamm: Darstellung der Apotheken, die für das eRezept ausgeschlossen sind (NES-Ignore Spalte).
- [x] __#1590__ - eRezept: Verwaltungsmodul für die KIM-Adressen.
- [x] __#1593__ - eRezept: erst nach Klicken auf ""PZN Hinzuf."" wird die Verordnung hinzugefügt. Dadurch kann man jetzt die Kassengruppe vor der Taxierung anpassen.
- [x] __#1594__ - ApoCONNECT: @-Rezepte - Export Spalten.
- [x] __#1596__ - eRezept: neue Tabellen für die Zusatzattributen und Rezeptänderungen wurden eingerichtet.
- [x] __#1602__ - Optionen - Verbindung - GKV/PKV Rezepte werden nicht übertragen - die Beschreibung der Option wurde optimiert.
- [x] __#1614__ - eRezept - die Dosierung bei der Freitextverordnung wird dargestellt.
- [x] __#1616__ - Volltext-Suche in folgenden Modulen:
- Artikelstamm (Eigene Artikel - Name)
- Arztstamm (Name, IK, LANR, Strasse, PLZ, Ort, RefNr., RefNr.2, Indikationsnr., ExtArztID, ExtArztID2)
- Kassenstamm (Kassennummer, IK, Kassenname, PLZ, Ort)
- Kassengruppen (ID, Kassengruppenname, Suchbegriff)
- externe Patientenstammdaten (ID, Name, Versichertennummer, Vorname, PatientenID)
- Patientenstammdaten (Name, Vorname, Versichertennummer,Strasse, Ort, Land)
- [x] __#1618__ 
- [x] __#1619__ 
- [x] __#1620__ - eRezept - Zusatzattribute: 7 (Wirkstoffverordnung), 10 (einzeln importierte Fertigarzneimittel (§ 73 Abs. 3 AMG)) sowie 15 (Zuzahlungsbefreiung) wurden implementiert.
- [x] __#1607__ - eRezept: Zusatzattribut und Rezeptänderungen wurden in der Rezeptliste dargestellt.
- [x] __#1621__ - eRezept: UI Komponente für Rezeptanforderung in der Taxierungsmaske, Auswahl der KIM-Adresse für Empfänger.
- [x] __#1625__ - eRezept PKV - bei dem Taxierungsvorgang wird der Rezepttyp automatisch auf PKV umgestellt.
- [x] __#1486__ - eRezept - Inhalt der technischen Tabellen (Queue Tabellen für Rezeptanforderung und Rezeptabruf) wurde dargestellt.

# Version 5.3.8.4 (öff. am 24.07.2023)
- [x] __#1608__ - Warnung "fehlender Wirkstoff" in der Herstellungsschnittstelle wurde rausgenommen.
- [x] __#1609__ - Rezeptliste: Sortierung über die erste Spalte (Typ) wurde aktiviert.
- [x] __#1615__ - Taxierung von Hilfsmitteln: Fehlermeldung in der Rezeptliste: "'xxxxxxxxxx' is not a valid integer value" wurde korrigiert

# Version 5.3.8.3 (öff. am 14.07.2023)
- [x] __#1589__ - Rezeptliste - Leistungsverbesserung der SQL-Abfrage in Bezug auf die Anzeige von Informationen über Kassenabsetzungen

# Version 5.3.8.2 (öff. am 10.07.2023)
- [x] __#1561__ - Externe Patientendaten - Einwilligung der Datenweiterleitung Auswahl über ComboBox, farbige Darstellung.
- [x] __#1566__ - ZYTO-Schnittstelle - Suchfunktion nach Vornamen und Geburtsdatum.
- [x] __#1576__ - Tabelle HRS_MESSAGE - neuer Index auf ERezeptID wurde hinzugefügt
- [x] __#1581__ - Tabelle ERP_VERORDNUNG - neue Spalte ERP_TIMESTAMP wurde eingerichtet

# Version 5.3.8.1 (öff. am 28.06.2023)
- [x] __#1542__ - Beim Kopieren/Korrigieren von AMG-Rezepten wurde die Option "Formel verwenden" automatisch deaktiviert.
Dadurch wurde ein anderer Preis (eventuell auch MwSt.) berechnet.
Betroffen sind die ABDA-Artikel ohne Taxierungsformel auf Artikelebene.

# Version 5.3.8.0 (öff. am 15.06.2023)
- [x] __#1232__ - Externer Artikelstamm: die Felder im Reiter Allgemein wurden so erweitert, dass sich die neuen langen Artikeltypen mit den Artikelinformationen nicht mehr überlappern.
- [x] __#1245__ - Modul Neues Rezept und @Rezept: die Icons bei den PKV Rezepten wurden angepasst (blaue Rezepte).
- [x] __#1411__ - Taxierungformeln wurden um die neue Variable IMPFRAB (Impfstoffrabatt) erweitert.
- [x] __#1420__ - Das Modul ABDA Update Freischaltung wurde aus dem Programm entfernt.
- [x] __#1432__ - Modul Tax-Checker: der geöffnete Dateiname (Vertragsdatei) wird in der Kopfzeile angezeigt.
- [x] __#1433__ - Modul Tax-Checker: Zeilenmarkierungen (Farben) werden jetzt nur in dem Feld Beschreibung dargestellt. Die Formel-Prüfroutine wurde optimiert und nur nach Bedarf ausgeführt.
- [x] __#1448__ - Standardansichten/Benutzeransichten: PKV - Auswahlbox In allen Ansichten werden standardmäßig nur die GKV Rezepte dargestellt. Mit der Checkbox kann man auf die PKV Rezepte umswitchen.
- [x] __#1449__ - Rezeptkopiervorgang:
Bei einem Kopiervorgang wurde zur Zeit die Patient-Gebührenbefreiung im Patientenstamm geprüft.
Hat sich der Status in der Zwischenzeit geändert, wurde ein Hinweis dargestellt.
Dieser Vorgang hat aber wenig Sinn bei den Patienten aus dem Ext.-Artikelstamm. Aus diesem Grund wurde diese Prüfung deaktiviert.
- [x] __#1456__ - Zyto-Schnittstelle: Produkte mit der Einheit "μg" wurden zur Zeit nicht richtig umgerechnet. Das wurde jetzt angepasst, die Promille sollen ab jetzt korrekt berechnet werden.
- [x] __#1470__ - ZYTO-Schnittstelle/Berechtigungen Für das Modul ZYTO-Schnittstelle können jetzt pro Benutzer die Berechtigungen gesetzt werden (Open/Config/Delete/Split)
- [x] __#1471__ - Neues Rezept: jetzt kann man pro Rezept beim Verlauf Kommentare hinterlegen.
- [x] __#1473__ - TaxChecker: die SOK werden jetzt in der Liste nicht mehr als SOK (PZN), sondern als SOK-Variablen dargestellt.
- [x] __#1474__ - Zyto-Schnittstelle: Sortieren der Spalten wurde optimiert.
- [x] __#1477__ - Zyto-Schnittstellle: neue Spalte ZUBEREITUNGID (interne ApoFAKT-ID) wurde als ApoFAKTID Spalte in der Gridd eingebaut.
- [x] __#1480__ - TaxChecker: neues Feld APOTYP wurde eingebaut.
- [x] __#1481__ - TaxChecker: Fehler bei Zeilenmarkierung wurde korrigiert.
- [x] __#1487__ - Musterrezepturen: Spalte 'Verwurf' wurde in 'zzgl. Verwurf' umbenannt. Wird der Verwurf auf 'Ja' gesetzt, wird er beim Taxieren in der Rezeptur automatisch berechnet.
- [x] __#1488__ - Artikelstamm: Kopierfunktion wurde eingebaut. Man kann jetzt z.B. die Arbeitspreise schneller eingeben.
- [x] __#1489__ - Artikelstammdaten: Taxierungsformeln für eigene Artikel. Man kann für die eigenen Artikel (z.B Arbeitspreise) Taxierungsformeln hinterlegen. Diese Formeln werden beim Taxieren von Rezepturen mitberücksichtigt.
- [x] __#1502__ - Neues Rezept: ein Rundungsfehler bei der Formelberechnung wurde behoben.
- [x] __#1506__ - Zyto-Schnittstelle: bei dem Taxiervorgang wird die verwendete Musterrezeptur-ID anzeigt. Dadurch kann man besser sehen, welche Musterrezeptur automatisch ausgewählt wurde.
- [x] __#1509__ - Taxieren von Sprechstundenbedarf - Zuzahlung darf nicht berechnet werden. 
- [x] __#1510__ - Tax-Checker: Optimierung mit Variablen SOKVOLL SOKERM
- [x] __#1515__ - Zyto-Schnittstelle: Lila Markierung (gesperrter Datensatz) wird jetzt nur dann angezeigt, wenn Verwurfsabrechnung in der Konfiguration aktiviert ist.
- [x] __#1516__ - eRezept: Beim Taxieren von eRezept wird die KassenIK aus der eVerordnung ausgelesen und dem Kostenträger zugeordnet. Ist der Kostenträger zu einer Kassengruppe zugeordnet, wird die Gruppe automatich ausgewählt. Ist der Kostenträger zu keiner Kassengruppe zugeordnet, wird die Standard-Kassengruppe ausgewählt. 
- [x] __#1518__ - Externe Patienten: Übertragung von Patientendaten, es wurde eine Checkbox Patientendaten ans RZ nicht übertragen eingerichtet.
- [x] __#1519__ - Zyto-Schnittstelle: es wurde die Substitution bei den Fertigarzneimitteln aus der Schnittstelle (günstigste FAMs) eingerichtet.
- [x] __#1520__ - Ext.-Artikelstamm: es wurde bei der Berechnungsweise der Stoffmenge eine leere Zeile hinzugefügt, mithilfe deren die gesetzte Berechnungsweise rückgängig gemacht werden kann.
- [x] __#1524__ - Externe Patienten/Neues Rezept: bei den Patienten, die wegen Datenschutz nicht zugestimmt haben, ihre Patientendaten ans RZ zu übertragen, kommt ein Pop-up-Fenster.
- [x] __#1530__ - Neues Rezept: es wurden neue Taxierungsvariablen (SOK-Variablen), die bei den Multiformeln angewendet werden, eingebaut.
MWST_SOK - Mehrwertsteuersatz, der im SOK übermittelt wird, prozentual
SOKVOLL - ergibt 1, wenn SOK des Artikels mit vollem MWST, sonst 0
SOKERM - ergibt 1, wenn SOK des Artikels mit ermäßigtem MWST, sonst 0
SOKMS - ergibt 1, wenn SOK des Artikels mit MWST (voll oder erm.), sonst 0
SOKOHNE - ergibt1, wenn SOK des Artikels mit steuerfrei ist, sonst 0

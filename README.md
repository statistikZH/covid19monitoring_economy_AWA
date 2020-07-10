# covid19monitoring_economy_AWA

## Grundlage 
Die Daten werden vom Amt für Wirtschaft und Arbeit des Kantons Zürich (AWAZH) geliefert und stammen aus dem Auszahlungssystem der Arbeitslosenkassen. Die Angaben beziehen sich auf die Anzahl der Betriebe und Beschäftigten, an die für den entsprechenden Monat Kurzarbeitsentschädigungsgelder ausbezahlt wurden.<br><br>

## Methodisches 
* Um möglichst detaillierte Daten zu veröffentlichen, werden pro Monat alle Branchen-Kategorien ausgewiesen, die für den jeweiligen Monat für mind. 10 Betriebe und mind. 100 Beschäftigte Kurzarbeitsgelder erhalten haben. Wenn eine Branche in einem Monat tiefere Zahlen ausweist, wird sie nicht separat aufgeführt, sondern der Restkategorie zugeteilt.  Dies hat zur Folge, dass nicht immer die gleiche Anzahl Branchen ausgewiesen wird.
* Es werden Betriebe bzw. Betriebsabteilungen mit Sitz im Kanton Zürich berücksichtigt (Standortprinzip, wobei der Eintrag im Betriebs- und Unternehmensregister (BUR) massgebend ist).
* Von Kurzarbeit betroffene Beschäftigte können ihren Wohnsitz auch ausserhalb des Kantons Zürich haben.
* Die Daten des AWAZH umfassen Zahlungen an Betriebe, insbesondere Zahlungen an Selbständige werden nicht vom AWAZH erfasst, sondern werden über die SVA Zürich im Rahmen der Erwerbsersatzordnung EO abgewickelt. 
* Da die Betriebe eine Kontrollperiode bis zu 3 Monate rückwirkend abrechnen können, sind die Daten erst mit 3-monatiger Verspätung stabil. Rückwirkende Anpassungen sind jedoch weiterhin möglich.

## Variablen 
<strong>kurzarbeitzh_ausbezahlt_betrieb</strong> = Kurzarbeit ausbezahlt Anzahl Betriebe<br>
<strong>kurzarbeitzh_ausbezahlt_besch</strong> = Kurzarbeit ausbezahlt Anzahl Beschäftigte<br>
<strong>share_ausbezahlt_betriebe</strong> = Anteil der ausbezahlten Betriebe an allen Betrieben auf Basis STATENT 2017<br>
<strong>share_ausbezahlt_besch</strong> = Anteil der ausbezahlten Beschäftigten an allen Beschäftigen auf Basis STATENT 2017<br>

## Nicht mehr aktualisierte Datensätze
Bis zum Zeitpunkt an dem erstmals Angaben zu den Auszahlungen vorlagen, wurden an dieser Stellen Daten zu den bewilligten Voranmeldungen publiziert. Diese Datenreihen werden nicht mehr fortgeführt, weil nun mit Angaben zu den Auszahlungen Daten zum tatsächlichen Ausmass der Kurzarbeit vorliegen. Informationen zum gegenwärtigen Stand der Voranmeldungen können beim Amt für Wirtschaft und Arbeit des Kantons Zürich nachgefragt werden. Die Informationen zu den alten Variablen sind im Ordner old_vars abgelegt.

## Weitere Informationen 
[Projektseite: "Gesellschafsmonitoring COVID19"](https://github.com/statistikZH/covid19monitoring) <br>
[Datenbezug](https://www.web.statistik.zh.ch/covid19_indikatoren_uebersicht/#/) <br>
[Visualisierung](https://www.web.statistik.zh.ch/cms_vis/covid19_indikatoren/) <br>


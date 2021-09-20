# covid19monitoring_economy_AWA

<strong> Dieses README bezieht sich auf nicht mehr fortgeführte Datensätze.</strong>

## Grundlage 
Die Daten werden vom Amt für Wirtschaft und Arbeit des Kantons Zürich (AWAZH) geliefert. Die Angaben beziehen sich auf die kumulierten bewilligten Voranmeldungen zur Kurzarbeit des jeweiligen Tages für den Kanton Zürich. Eine bewilligte Voranmeldung erlaubt einem Betrieb, für den Zeitraum der nächsten sechs Monate Kurzarbeitsgelder zu beantragen. Es kann sein, dass ein Betrieb von diesem Recht nicht Gebrauch macht. Es ist zudem möglich, dass die Angaben zur Anzahl der voraussichtlich betroffenen Arbeitnehmenden abweicht von der Anzahl Arbeitnehmenden, für die Kurzarbeitsgelder beantragt werden.<br><br>



## Methodisches 

* Es können nur Betriebe bzw. Betriebsabteilungen beim AWAZH eine Voranmeldung einreichen, wenn der Sitz im Kanton Zürich ist (Standortprinzip, wobei der Eintrag im Betriebs- und Unternehmensregister (BUR) massgebend ist).
* Die voraussichtlich von Kurzarbeit betroffenen Arbeitnehmenden können ihren Wohnsitz auch ausserhalb des Kantons Zürich haben. 
* Die Daten des AWAZH umfassen nur Kurzarbeits-Voranmeldungen von Betrieben. Zu erwähnen ist vor allem, dass die Voranmeldungen von Selbständigen nicht vom AWAZH erfasst werden.
* Aufgrund der Arbeitsprozesse kann es rückwirkend zu Veränderungen der Daten kommen. Etwa wenn Gesuche aufgrund veränderter Bewilligungskriterien erneut geprüft werden müssen (uns somit ein neues Bewilligungsdatum erhalten). 
* Für die Zeit bis zum 5. April liegen keine Tageswerte vor. Der kumulierte Stand an diesem Tag ist im CSV 'Economy_AWA_total_bis_5april' enthalten. Auch hier kann es rückwirkend zu Anpassungen kommen.


## Variablen 

<strong>kum_kurzarbeitzh_bew_betrieb </strong> = Kumulierte bewilligte Voranmeldungen Kurzarbeit Betriebe<br>
<strong>kum_kurzarbeitzh_bew_arbeitn</strong> = Kumulierte bewilligte Voranmeldungen Kurzarbeit voraussichtlich betroffene Arbeitn.

## Veraltete Variablen
Aufgrund einer Anpassung der administrativen Prozesse werden die beiden folgenden Variablen nicht mehr aktualisiert:

<strong>kurzarbeitzh_bew_betrieb </strong> = Anzahl der an Tag x bewilligte Voranmeldungen Kurzarbeit (=Anzahl Betriebe)<br>
<strong>kurzarbeitzh_bew_arbeitn</strong> = Anzahl der voraussichtlich von den  an Tag x bewilligten Voranmeldungen betroffenen Arbeitnehmenden

Die Variablen werde nicht mehr aktualisiert, weil bereits erfolgte Bewilligungsentscheide aufgrund von veränderten Bezugsbedingungen angepasst werden. So haben beispielsweise am Anfang des Monats März nicht alle Unternehmen für 6 Monate Kurzarbeit eingereicht, sondern nur  für 3, weil dieser Bezugsrahmen erst später vom Bundesrat so freigegeben wurde. Diese Entscheide werden nun alle ersetzt. Eine Fortführung der Zeitreihe macht deshalb inhaltlich keinen Sinn.


## Weitere Informationen 
[Projektseite: "Gesellschafsmonitoring COVID19"](https://github.com/statistikZH/covid19monitoring) <br>
[Datenbezug](https://www.web.statistik.zh.ch/covid19_indikatoren_uebersicht/#/) <br>
[Visualisierung](https://www.web.statistik.zh.ch/cms_vis/covid19_indikatoren/) <br>


# Technische Indikatoren 

## Einleitung

Indikatoren ganz allgemein sind Kennzahlen, die einen Vergleich unterschiedlicher Werte ermöglichen. Im Zusammenhang mit
Kapitalmarkten und der Markttechnik sind das Kennzahlen, die sich ausschließlich aus den Kursen und Umsatzen der Vergangenheit
erstellen lassen.
Viele Kennzahlen generieren bei Erreichung bestimmter Niveaus direkt Handelssignale (Kaufen, Verkaufen). Andere unterstützen den 
Analysten dabei, zu erkennen, welche Indikatoren bei der herrschenden Marktlage überhaupt sinnvoll einzusetzen sind.
Wahrend Indikatoren  alle  möglichen Werte annehmen können, schwanken Oszillatoren um einen bestimmen Mittelwert  und  können
nach oben und unten begrenzt sein. Weiterhin können die Indikatoren nach ihren Einsatzgebieten gegliedert werden.
Viele Indikatoren lassen sich nicht eindeutig einer Kategorie zuordnen, da sie Komponenten verschiedener Berechnungen enthalten. 
Die Einteilung dient dem Verstandnis, dass Indikatoren bestimmte Aufgaben haben und manchmal nur in Kombination sinnvolle
Signale liefern.

## Indikatoren

### Trendfolgeindikatoren

#### Einleitung
Indikatoren dieser Gruppe versuchen, einen vorherrschenden Trend, also die
Kursrichtung zu identifizieren. Sie laufen dem aktuellen Trend hinterher, d.h. Handelssignale können erst generiert werden, wenn
sich ein bestimmter Trend etabliert hat. Sie sind also in Trendphasen einsetzbar – je nachhaltiger eine Trendphase, desto
erfolgreicher sind sie.  In Phasen von Seitwartsbewegungen
Liefern sie Fehlsignale. Es werden ledigliche reine Trendphasen angezeigt, nicht aber  Übertreibungsphasen  nach  oben  oder
unten  –  dafür  werden  Oszillatoren verwendet.

#### MA – Moving Average
Der wohl bekannteste Trendfolgeindikator ist der gleitende Durchschnitt (Moving Average). Er berechnet nur einen
Durchschnittskurs und glattet somit den Kursverlauf. In der Praxis kommen verschiedene gleitende Durchschnitte vor.
Durchbricht der Kurs den MA von unten, ergibt sich das Handelssignal kaufen, wird der Durchschnitt von oben durchbrochen,
wird das Signal verkaufen generiert.

#### SMA – Simple Moving Average
Hierbei wird das einfache arithmetische Mittel berechnet.  Je nach Lange des Betrachtungszeitraumes t, werden kurz-,
mittel-oder langfristige Trends angezeigt. Gangige Zeitraume sind 38, 100 und 200 Tage.

#### WMA – Weighted Moving Average
Beim gewichteten gleitenden Durchschnitt wird jeder Kurs unterschiedlich gewichtet. Im Allgemeinen werden die weiter
zurückliegenden Kurse weniger gewichtet, als die aktuelleren.
 
#### EMA – Exponential Moving Average
Der exponentielle gleitende Durchschnitt berechnet sich iterativ aus samtlichen vergangenen Kursen, d.h. bei unterschiedlichen
Betrachtungszeitraumen/vorliegenden historischen Daten, errechnen sich unterschiedliche EMAs trotz Betrachtung des identischen
Titels.

EMAt = EMAt−1 + (SF • (Ct − EMAt−1)) 

EMAt = SF • Ct + (1 − SF) • EMAt−1

Vorteil der gewichteten MAs (WMA, EMA) ist, dass diese schneller auf Trendwechsel  reagieren,  als  die  einfachen  MAs,  da
die  jüngeren  Kurse  höher gewichtet  werden,  als  die  alteren.  In der Abbildung 3 sind die verschiedenen MAs am
Beispiel der Dax-Werte vom 1.5.  bis 1.11.  2007 – also über  sechs Monate – dargestellt. Dieser Zeitraum wird für alle hier
gezeigten BeispielCharts verwendet.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech1.png)

Abbildung 3: Charts verschiedener Moving Averages

#### MACD – Moving Average Convergence/Divergence System
Dieser Indikator kann sowohl als Trendfolger als auch als Oszillator dienen. Beim MACD handelt es sich um eine Kombination aus
zwei Linien. Die erste wird  aus  der  Differenz  zweier  EMAs, eines  kürzeren  und  eines  langeren,  des zu betrachtenden
Kurses gebildet. Die zweite Linie ergibt sich als EMA dieser Differenz, der sogenannte Trigger.
Die MACD-Linie schwankt also um die Null-Linie und je größer dieser Abstand  ist,  desto  größer  ist  die  Divergenz:  die
EMAs  gehen  auseinander.  Das heißt, der vorherrschende Trend intensiviert sich. Kreuzt die MACD-Linie den Trigger von unten,
wird ein Kaufsignal signalisiert, andernfalls ein Verkaufsignal.  Je  größer  der  Abstand  zur  Null-Linie,  desto
erfolgreicher  sind  die Signale, da dann die Trendintensitat größer ist, als in der Nahe der Null-Linie. Kaufsignal und
Verkaufsignal bedeuten Kurs wird steigen bzw. Kurs wird fallen.
Wird eine Divergenz zwischen MACD-Linie und Kursverlauf beobachtet, deutet dies auf einen Trendwechsel hin. In der Abbildung 4
ist ein MACD mit Trigger abgebildet.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech2.png)


![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech3.png)

Abbildung 4: MACD–Chart

#### CCI - Commodity Channel Index
Der CCI  quantifiziert den Abstand zu einem SMA der taglichen Durchschnitts- kurse. Der tagliche Durchschnittskurs berechnet
sich alsarithmetisches Mittel von Tageshoch, -tief  und -schlusskurs.  Wird dabei ein bestimmtes Maß überschritten, wird ein
beginnender Trend unterstellt (s. Abb. 5, S. 7). Als gangiger Abstand für die Generierung von Handelssignalen dient der
Abstand von 100:

•	CCI steigt über +100: kaufen

•	CCI sinkt unter +100: halten

•	CCI sinkt unter −100: verkaufen

•	CCI steigt über −100: halten

Schwankt der CCI also im Band der beiden Signallinien, empfiehlt sich die Verwendung eines Oszillators, da der Kurs keinem Trend
folgt [10]. In Abbildung 5 ist der Verlauf zu sehen.


![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech4.png)

Abbildung 5: CCI–Chart
Im ersten Schritt wird pro Periode (Tag, Woche, Monat etc.) der sogenannte signifikante Kurs  ermittelt. Dieser berechnet sich
als arithmetisches Mittel aus Höchst-, Tiefst- und Schlusskurs. Daraus errechnet sich ein einfacher MA (also ein  SMA  des
signifikaten  Kurses,  standardmaßig  über  zwanzig  Perioden).  Im dritten Schritt wird schließlich der CCI als Differenz
von signifikantem Kurs und seinem SMA geteilt durch das 0,015-fache der Standardabweichung vom typischen  Kurs  zum  SMA
berechnet.  Der  Faktor  0, 015  ist  eine  willkürliche Konstante, die vom Entwickler Lambert vorgeschlagen wurde, so dass
sich der Indikator hauptsachlich im Band zwischen −100 und +100 befindet.

### Umsatzindikatoren

#### Einleitung
Die  Umsatze  haben  bei  der  technischen  Analyse  sehr  hohe  Relevanz.  Die  Indikatoren dieser Gruppe weisen auf
Volumentrends hin und können in Zusammenhang mit andern Indikatoren aber auch selbstandig Handelssignale liefern.

#### OBV – On Balance Volume
Dieser  Indikator  soll  aufzeigen,  ob  Liquiditat  in  ein  Papier  hinein-  oder  aus diesem herausfließt. Der OBV
entspricht einem Umsatzchart, der mit der Tages-Veranderung der Kurse ins Verhaltnis gesetzt wird. Bei steigenden Kursen
wird das Volumen zum OBV des Vortages addiert, bei fallenden wird es abgezogen. Steigen also die Kurse, ohne dass der Indikator
diese Bewegung mitmacht, es also zu einer Divergenz kommt, befinden sich die Kurse an einem Top und fallende Kurse könnten
folgen. In Verbindung mit seinem MA können somit Handelssignale generiert werden.
Die Berechnung ist abhangig vom heutigen Schlusskurs:

ist dieser höher als der gestrige:     OBV = OBVgestern +  Volumen heute

ist dieser niedriger als der gestrige: 	OBV = OBVgestern − Volumen heute

sind beide gleich:	                    OBV = OBVgestern

Die Annahme, dass sich der gesamte Umsatz an einem positiven Tag aus Kaufen zusammensetzt, ist eine Vereinfachung und recht
fragwürdig. Daher gilt der OBV heute als veraltet.
Es wird auch kritisiert, dass der OBV der Starke einer Kursbewegung keinerlei Beachtung schenkt und es mittlerweile
Indikatoren gibt, die das Kurs/Volumen-Verhaltnis detaillierter betrachen (s. ADL).

#### Accumulation/Distribution Line
Diese Linie stellt eine Weiterentwicklung des OBV-Konzeptes dar, indem hier ein fortlaufender Index als Volumenindikator
berechnet wird und die heutige Kursentwicklung mit den Umsatzen gewichtet wird.  In  Abhangigkeit  vom Verhaltnis
Schlusskurs  zu  Durchschnittskurs  eines  Tages  wird  ein  bestimmter Prozentsatz des Tagesumsatzes zum ADL-Wert des Vortages
addiert bzw. subtrahiert. Liegt z.B. der Schlusskurs über dem Mittel, wird ein Teil addiert.
Im Vergleich zum OBV wird also nur jeweils ein angemessener Teil des Umsatzes berücksichtigt.  Beide  Indikatoren  sind  in
Abbildung  6  für  die  SAP-Aktie zu sehen.

![](https://github.com/Efahim/Analise/blob/master/Documents/Images/tech5.png)

Abbildung 6: ADL– und OBV–Chart der SAP-Aktie
